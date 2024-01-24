---
title: Essays
layout: page
permalink: /essays.html
---
<ul>
{% for e in site.essays%}
<li><a href="{{ e.url | relative_url}}">{{e.title}}</a></li>{% endfor %}
</ul>

<p>{% for e in site.essays%}
{{e.title}},{{ e.url | relative_url}},Essays<br>{% endfor %}</p>