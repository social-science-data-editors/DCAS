---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
image: https://datacodestandard.org/assets/img/logo-800.png
---

{% for rule in site.data.rules %}
{% if rule.group %}| | **{{ rule.group }}** |
{% endif -%}
| {{ forloop.index}} | {{ rule.topic }} | {{ rule.description }}{% endfor %}

