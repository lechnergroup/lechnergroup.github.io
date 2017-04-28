---
layout: page
title: Publications
permalink: /publications/
---

<ul>
{% for publication in site.data.publications %}
<p>  
  <li>
  <a href="{{publication.link}}"> {{ publication.name }} </a>
      <br>
      {{publication.authors}}
      <br>
      {{publication.reference}}
  </li>
  </p>
{% endfor %}
</ul>