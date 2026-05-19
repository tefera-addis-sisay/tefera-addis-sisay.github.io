---
layout: archive
title: "Projects"
permalink: /project/
author_profile: true
---

{% include base_path %}

## Selected Projects

Below are my research and development projects in networking, security, and intelligent systems.

<div class="projects-grid">

{% for post in site.project reversed %}
  <div class="project-card">
    <h3>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h3>

    <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
  </div>
{% endfor %}

</div>
