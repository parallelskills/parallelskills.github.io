---
title: Blog
layout: page
description: This page has links for our recent blog posts.
intro_image: "images/Blog.jpg"
intro_image_absolute: true
intro_image_hide_on_mobile: true
---
# Recent Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>