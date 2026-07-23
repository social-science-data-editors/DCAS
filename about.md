---
layout: home
title: About
list_title: Announcements
permalink: /about/
image: https://datacodestandard.org/assets/img/logo-800.png
---
[DCAS](/) is a standard for sharing research code and data, endorsed by [leading journals](/journals) in social sciences. It is maintained by the [Social Science Data Editors](https://social-science-data-editors.github.io/).

Authors: {% for author in site.authors %}{% unless forloop.first %}, {% endunless %}{% if forloop.last %} and {% endif %}[{{ author.name }}]({{ author.url }}){% endfor %}

Current version: {{ site.version }} ({{ site.date }})

> ## Please cite as
> {% for author in site.authors %}{% unless forloop.first %}, {% endunless %}{% if forloop.last %} and {% endif %}{{ author.short }}{% endfor %}. 2022. "Data and Code Availability Standard [Version {{ site.version }}]." Website. {{ site.url }} https://doi.org/{{ site.doi }}

For machine-readable citation, see [CITATION.cff here](https://github.com/social-science-data-editors/DCAS).

## License

This work is licensed under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/). To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work. This means you can use, modify, and distribute this work without permission or attribution, though attribution is appreciated.
