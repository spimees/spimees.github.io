---
layout: default  
title: "Personal webpage"
---

### Spimees

Welcome to my page!

I am a software engineer building mainly desktop application and doing research on concurrency in my free time.


Below is the list of my posts

<span id="posts"><a href="#" class="custom-heading-3">Posts</a></span>
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_string }} <a href="{{ post.url }}">{{ post.title }}</a> 
    </li>
  {% endfor %}
</ul>
