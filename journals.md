---
layout: page
title: Journals
permalink: /journals/
image: https://datacodestandard.org/assets/img/logo-800.png
---
The following journals endorse the Data and Code Availability Standard.

<ol>
{% assign sorted_journals = site.data.journals | sort: 'name' %}
{% for journal in sorted_journals %}

  <li>    {% if journal.url %}<a href="{{ journal.url }}">{% endif %}{{ journal.name }}{% if journal.url %}</a>{% endif %}
          {% if journal.twitter %}<a href="https://twitter.com/{{ journal.twitter }}"><i class="fa-brands fa-twitter socialmediaicons" aria-hidden="true"></i></a>{% endif %}
          {% if journal.linkedin %}<a href="{{ journal.linkedin }}"><i class="fa-brands fa-linkedin socialmediaicons" aria-hidden="true"></i></a>{% endif %}
          {% if journal.mastodon %}<a href="https://{{ journal.mastodonsrv }}/@{{ journal.mastodon }}"><i class="fa-brands fa-mastodon socialmediaicons" aria-hidden="true"></i></a>{% endif %}
          {% if journal.bluesky %}<a href="https://bsky.app/profile/{{ journal.bluesky }}"><i class="fa-brands fa-bluesky socialmediaicons" aria-hidden="true"></i></a>{% endif %}
  </li>
{% endfor %}
  </ol>

Individual journal policies may differ slightly. To ensure full compliance, check the policies and submission guidelines of the journal.

To request inclusion and to learn how to show endorsement of DCAS, see [How to adopt and endorse DCAS](/adopting/).