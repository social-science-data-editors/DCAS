---
layout: page
title: About
permalink: /about/
---
[DCAS](/) is a standard for sharing research code and data, endorsed by [leading journals](/journals) in social sciences. It is maintained by the [Social Science Data Editors]().

Authors: {% for author in site.authors %}{{ author.name }}{% unless forloop.last %}, {% endunless %}{% endfor %}

Current version: {{ site.version }} ({{ site.date }})

> ## Please cite as
> Koren, Miklós, Lars Vilhuber, Marie Connolly, and Joan Llull. 2022. "Data and Code Availability Standard [Version {{ site.version }}]." Website. http://datacodestandard.org
