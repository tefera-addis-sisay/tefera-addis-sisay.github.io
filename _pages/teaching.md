---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

## Courses I Teach

Below are undergraduate courses I have taught at Bahir Dar Institute of Technology.

<div class="teaching-grid">

{% for post in site.teaching reversed %}
  <div class="teaching-card">

    <h3 class="teaching-title">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h3>

    <p class="teaching-meta">
      Undergraduate Course • Bahir Dar Institute of Technology • 2025
    </p>

    <p class="teaching-summary">
      {{ post.excerpt | strip_html | truncate: 180 }}
    </p>

  </div>
{% endfor %}

</div>
