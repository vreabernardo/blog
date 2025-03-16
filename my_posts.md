---
layout: page
title: My Posts
permalink: /my-posts/
---

<h1>My Custom Posts</h1>

<div class="post-list">
  {% for post in site.my_posts %}
    <div class="post-item" style="margin-bottom: 20px;">
      <p class="post-meta" style="margin-bottom: 0;">
        {% if post.custom_date %}
          {{ post.custom_date | date: site.minima.date_format }}
        {% endif %}
      </p>
      <h3 style="margin-top: 0;">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h3>
    </div>
  {% endfor %}
</div> 