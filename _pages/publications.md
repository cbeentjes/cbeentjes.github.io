---
layout: archive
permalink: /publications/
author_profile: true
pub_last_update: 2020-07-14
pre_last_update: 2020-07-14
pro_last_update: 2020-04-01
---

{% if site.author.googlescholar %}
  <i class="fas fa-fw fa-graduation-cap"></i> For an up to date list see <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

Preprints
=====
<sub><sup>(last updated {{ page.pre_last_update | default: "2020-04-01" | date: "%-d %B %Y" }})</sup></sub>
<ul>{% for post in site.preprints reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>

Publications
=====
<sub><sup>(last updated {{ page.pub_last_update | default: "2020-04-01" | date: "%-d %B %Y" }})</sup></sub>
<ol reversed>{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ol>

Conference and workshop proceedings
=====
<sub><sup>(last updated {{ page.pro_last_update | default: "2020-04-01" | date: "%-d %B %Y" }})</sup></sub>
<ul>{% for post in site.proceedings reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>
