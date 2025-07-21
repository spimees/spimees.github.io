---
layout: default  
title: "Personal webpage"
---

### Spimees

Welcome to my page!

I am a dosftware engineer focusing on developing desktop application, doing independant research on concurrency in my free time.


Blow is the list of my posts

<span id="posts"><a href="#" class="custom-heading-3">Posts</a></span>
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_string }} <a href="{{ post.url }}">{{ post.title }}</a> 
    </li>
  {% endfor %}
</ul>
