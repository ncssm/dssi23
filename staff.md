---
layout: page
title: Staff
description: A listing of all the people involved this week.
---

# Workshop Staff

A big thanks to all the folks who worked to make this week possible!

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign speakers = site.staffers | where: 'role', 'Speaker' %}
{% assign num_speakers = speakers | size %}
{% if num_speakers != 0 %}
## Speakers

{% for staffer in speakers %}
{{ staffer }}
{% endfor %}
{% endif %}
