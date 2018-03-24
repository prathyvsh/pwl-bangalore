---
layout: default
title: Talks
permalink: /talks/
---

<ul id="talk-listing">
  {% for meetup in site.data.meetup %}

  <li>
    <h2>
      <a href="#{{meetup.name | slugify }}"
         name="{{meetup.name | slugify }}">  
         {{ meetup.name }}
         ¶ 
      </a>
      <a href="{{meetup.link}}">⤤</a>
    </h2>

    <div class="description">
      {{ meetup.description}}
    </div>

  </li>
{% endfor %}
</ul>
