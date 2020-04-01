---
layout: archive
permalink: /talks/
author_profile: true
last_update: 2020-04-01
redirect_from:
  - /presentations
---

{% include base_path %}

Presentations
=====
<sub><sup>(last updated {{ page.last_update | default: "2020-04-01" | date: "%-d %B %Y" }})</sup></sub>
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}</ul>

