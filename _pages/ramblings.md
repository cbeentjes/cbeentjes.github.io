---
layout: archive
permalink: /ramblings/
theses_last_update: 2020-04-01
notes_last_update: 2020-04-01
author_profile: true
---

A collection of small and bigger projects written, mainly, during my education that have not been published. **Note that these pieces of work have not been formally peer-reviewed and will inevitably contain flaws.** Code for algorithms or to generate figures for some of the work is available in the corresponding Bitbucket repositories.

{% include base_path %}

Theses
=====
<sub><sup>(last updated {{ page.theses_last_update | default: "2020-04-01" | date: "%-d %B %Y" }})</sup></sub>

<ul>{% for post in site.theses reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>

Notes, reviews and other work
=====
<sub><sup>(last updated {{ page.theses_last_update | default: "2020-04-01" | date: "%-d %B %Y" }})</sup></sub>

<ul>{% for post in site.notes reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>
