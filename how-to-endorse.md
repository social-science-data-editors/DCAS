---
layout: page
title: How to endorse DCAS
image: https://datacodestandard.org/assets/img/logo-800.png
---

The [Journal](/journals/) page lists those journals that have explicitly endorsed this standard. This page describes how to record endorsement on this site, and how to signal endorsement on the journal website. 

## Denoting Endorsement and Compliance {#endorsement}

Endorsing journals can signal endorsement and compliance on their website by adding the following to the page or section describing the data and code availability policy:

> ![](/assets/img/DCAS-1.0.png) The [**JOURNAL NAME**] endorses DCAS, the [Data and Code Availability Standard](https://datacodestandard.org/) [v{{ site.version }}], and its data and code availability policy is compatible with DCAS.


Inclusion of a journal into the above list of endorsers is encouraged and can be achieved via pull request against the [repository](https://github.com/social-science-data-editors/DCAS) of this website.

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

## Recording Endorsement on this Site

To add your journal to the list of endorsers on this site, please submit a pull request against the [repository's `journals.csv` file](https://github.com/social-science-data-editors/DCAS/blob/main/_data/journals.csv). The file has the following columns:


- `name`: Full journal name
- `url`: URL of the journal homepage
- `twitter`: URL of the journal's X profile (optional)
- `mastodon`: the journal's Mastodon handle (optional)
- `mastodonsrv`: the Mastodon server for the journal's handle (optional)
- `linkedin`: URL of the journal's LinkedIn profile (optional)

The pull request will be reviewed and merged by the DCAS maintainers. Once merged, the journal will appear on the [Journal](/journals/) page within 24 hours.