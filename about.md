---
layout: page
title: About
permalink: /about/
---
[DCAS](/) is a standard for sharing research code and data, endorsed by [leading journals](/journals) in social sciences. It is maintained by the [Social Science Data Editors]().

Authors: {% for author in site.authors %}{% unless forloop.first %}, {% endunless %}{% if forloop.last %} and {% endif %}[{{ author.name }}]({{ author.url }}){% endfor %}

Current version: {{ site.version }} ({{ site.date }})

> ## Please cite as
> {% for author in site.authors %}{% unless forloop.first %}, {% endunless %}{% if forloop.last %} and {% endif %}{{ author.short }}{% endfor %}. 2022. "Data and Code Availability Standard [Version {{ site.version }}]." Website. {{ site.url }} https://doi.org/{{ site.doi }}

For machine-readable citation, see [CITATION.cff here](https://github.com/social-science-data-editors/DCAS).