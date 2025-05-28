---
layout: splash
permalink: /publications/
author_profile: false
---

## Selected Publications

<ul class="pub-list">
{% for pub in site.data.publications %}
  <li>
    {{ pub.authors }}. <strong>{{ pub.title }}</strong>.
    <a href="{{ pub.doi }}" target="_blank"><em>{{ pub.journal }}</em> {{ pub.volume }} ({{ pub.year }}), {{ pub.pages }}</a>.
  </li>
{% endfor %}
</ul>







