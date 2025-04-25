---
layout: page
title: Godot Development
subtitle: My Game Development Journey
---

{% for post in site.godot %}
<article class="post-preview">
  <a href="{{ post.url | relative_url }}">
    <h2 class="post-title">{{ post.title }}</h2>
    {% if post.subtitle %}
      <h3 class="post-subtitle">{{ post.subtitle }}</h3>
    {% endif %}
  </a>
  <div class="post-entry">
    {{ post.excerpt | strip_html | truncatewords: 50 }}
  </div>
  <p class="post-meta">Posted on {{ post.date | date: "%B %-d, %Y" }}</p>
</article>
{% endfor %}