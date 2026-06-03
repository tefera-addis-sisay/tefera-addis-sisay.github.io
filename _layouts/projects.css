---
layout: default
---

<div class="projects-page">

  <div class="lab-header">
    <h1>{{ page.title }}</h1>
    <p>
      Selected research and development work in networking, security, and intelligent systems.
    </p>
  </div>

  <div class="projects-grid">

    {% for post in site.projects %}

    <div class="project-card">

      <!-- TITLE + STATUS -->
      <div class="project-top">
        <a href="{{ post.url | relative_url }}" class="project-title">
          {{ post.title }}
        </a>

        {% if post.status %}
        <span class="status {{ post.status | downcase }}">
          {{ post.status }}
        </span>
        {% endif %}
      </div>

      <!-- EXCERPT -->
      <p class="project-excerpt">
        {{ post.excerpt }}
      </p>

      <!-- TAGS -->
      {% if post.tags %}
      <div class="project-tags">
        {% for tag in post.tags %}
        <span class="tag">{{ tag }}</span>
        {% endfor %}
      </div>
      {% endif %}

      <!-- ACTION BUTTONS -->
      <div class="project-actions">

        <a href="{{ post.url | relative_url }}" class="btn">
          View Details →
        </a>

        {% if post.github %}
        <a href="{{ post.github }}" target="_blank" class="btn secondary">
          GitHub
        </a>
        {% endif %}

      </div>

    </div>

    {% endfor %}

  </div>

</div>
