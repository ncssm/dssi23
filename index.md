---
layout: home
title: Home
nav_order: 1
nav_exclude: false
permalink: index.html
---

# Thank You for an AMAZING 2023 Data Science Summer Institute

![Group Photo](https://raw.githubusercontent.com/ncssm/dssi23/7e9f6fd14f44c5e5c15498204cfaafacc1f8901d/assets/images/BFH_0014_cropped.jpg)

{: .mb-2 }
NCSSM-Morganton, July 10-14, 2023
{: .mb-2 .fs-6 .text-grey-dk-000 }

[Jupyter Link](https://demohub.ncssm.edu){: .btn .btn-orange} [Sync Materials](https://demohub.ncssm.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fncssm%2Fdssi23-materials&urlpath=lab%2Ftree%2Fdssi23-materials%2F&branch=main){: .btn .btn-purple}

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
