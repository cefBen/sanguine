---
layout: default
---

## Key Papers

<ul>
  {% for paper in site.data.papers %}
    <li>
      <strong>{{ paper.title }}</strong> ({{ paper.year }}) – 
      <a href="{{ paper.link }}" target="_blank">View</a>
    </li>
  {% endfor %}
</ul>
