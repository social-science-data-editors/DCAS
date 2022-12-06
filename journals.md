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
          {% if journal.twitter %}<a href="https://twitter.com/{{ journal.twitter }}"><i class="fa-brands fa-twitter socialmediaicons" aria-hidden="true"></i>@{{ journal.twitter }}</a>{% endif %}
          {% if journal.linkedin %}<a href="{{ journal.linkedin }}"><i class="fa-brands fa-linkedin socialmediaicons" aria-hidden="true"></i></a>{% endif %}
          {% if journal.mastodon %}<a href="https://{{ journal.mastodonsrv }}/@{{ journal.mastodon }}"><i class="fa-brands fa-mastodon socialmediaicons" aria-hidden="true"></i>@{{ journal.mastodon}}@{{ journal.mastodonsrv }}</a>{% endif %}
  </li>
{% endfor %}
  </ol>

Individual journal policies may differ slightly. To ensure full compliance, check the policies and submission guidelines of the journal.

