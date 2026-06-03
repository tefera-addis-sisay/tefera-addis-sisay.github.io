---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Selected Projects

Below are my research and development projects in networking, security, and intelligent systems.

<div class="projects-grid">

{% for post in site.projects reversed %}

  <div class="project-card">

    <h3 class="project-title">
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    </h3>

    <p class="project-excerpt">
      {{ post.excerpt | strip_html | truncate: 160 }}
    </p>

  </div>

{% endfor %}

</div>
