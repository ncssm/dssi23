---
layout: home
title: Home
nav_order: 1
nav_exclude: false
permalink: index.html
---

# Welcome to the Data Science Summer Institute

{: .mb-2 }
NCSSM-Morganton, July 10-14, 2023
{: .mb-2 .fs-6 .text-grey-dk-000 }

[Jupyter Link](https://demohub.ncssm.edu){: .btn .btn-organge}

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}
