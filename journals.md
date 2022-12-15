---
layout: page
title: Journals
permalink: /journals/
---
The following journals endorse the Data and Code Availability Standard.

<ol>
{% for journal in site.data.journals %}
<!-- {{ forloop.index}}. -->
  <li>    {% if journal.url %}<a href="{{ journal.url }}">{% endif %}{{ journal.name }}{% if journal.url %}</a>{% endif %}
          {% if journal.twitter %}<a href="https://twitter.com/{{ journal.twitter }}"><i class="fa-brands fa-twitter socialmediaicons" aria-hidden="true"></i></a>{% endif %}
          {% if journal.linkedin %}<a href="{{ journal.linkedin }}"><i class="fa-brands fa-linkedin socialmediaicons" aria-hidden="true"></i></a>{% endif %}
          {% if journal.mastodon %}<a href="https://{{ journal.mastodonsrv }}/@{{ journal.mastodon }}"><i class="fa-brands fa-mastodon socialmediaicons" aria-hidden="true"></i></a>{% endif %}
  </li>
{% endfor %}
  </ol>

Individual journal policies may differ slightly. To ensure full compliance, check the policies and submission guidelines of the journal.

## Denoting Endorsement and Compliance

Endorsing journals can signal endorsement and compliance on their website by adding the following to the page or section describing the data and code availability policy:

> ![](/assets/img/DCAS-1.0.png) The [**JOURNAL NAME**] endorses DCAS, the [Data and Code Availability Standard](https://datacodestandard.org/) [v{{ site.version }}], and its data and code availability policy is compatible with DCAS.

### Markdown code

```
![Link to DCAS Icon]({{ site.url }}/assets/img/DCAS-1.0.png) 
The [**JOURNAL NAME**] endorses DCAS, 
the [Data and Code Availability Standard](https://datacodestandard.org/)
[v{{ site.version }}], and its data and code availability policy is 
compatible with DCAS.
```
### HTML Code

```html
<img src="{{ site.url }}/assets/img/DCAS-1.0.png"/> The [**JOURNAL NAME**]
endorses DCAS, the <a href="https://datacodestandard.org/">Data and Code
Availability Standard</a> [v{{ site.version }}], and its data and code
availability policy is compatible with DCAS.
```

### Icons
Use any of these icons. PNG works on all sites. SVG should work on most sites

| PNG version | SVG version |
|---|---|
| ![DCAS icon small](/assets/img/DCAS-1.0.png) | ![DCAS icon small](/assets/img/DCAS-1.0.svg) |
| ![DCAS icon large](/assets/img/DCAS-1.0-large.png) | ![DCAS icon small](/assets/img/DCAS-1.0-large.svg) |