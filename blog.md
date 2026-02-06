---
layout: page
title: Blog
permalink: /blog/
---

Welcome to my blog! This is where I document my journey exploring AI tools and upskilling in data science and analytics engineering. 

I use this space to share projects I'm working on, lessons learned while experimenting with new technologies, and insights from hands-on learning. Whether I'm building data pipelines, testing modern analytics tools, or diving into machine learning techniques, I'll write about the process, challenges, and takeaways.

---

## Recent Posts

{% for post in site.posts %}
  <article class="post-preview">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
    <p>{{ post.excerpt }}</p>
    <a href="{{ post.url }}" class="read-more">Read more →</a>
  </article>
  <hr>
{% endfor %}

<style>
.post-preview {
  margin-bottom: 30px;
}

.post-preview h3 {
  margin-bottom: 5px;
}

.post-preview h3 a {
  color: #0366d6;
  text-decoration: none;
}

.post-preview h3 a:hover {
  text-decoration: underline;
}

.post-meta {
  color: #666;
  font-size: 0.9em;
  margin-bottom: 10px;
}

.read-more {
  color: #0366d6;
  text-decoration: none;
  font-weight: bold;
}

.read-more:hover {
  text-decoration: underline;
}
</style>
