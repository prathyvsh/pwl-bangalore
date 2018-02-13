---
layout: page
title: Talks
permalink: /talks/
---

<ul>
  {% for meetup in site.data.meetup %}

  <li>
    <h2>
      {{ meetup.name }}
      <a href="{{meetup.link}}"> 🌐 </a>
    </h2>

    <div class="description">
      {{ meetup.description}}
    </div>

  </li>
{% endfor %}
</ul>
