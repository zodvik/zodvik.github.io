---
layout: default
title: Home
---

# hi!

I'm Nikhil, a software engineer based in India. I am an early adoptor and like to run things when they are in beta.

You can reach me at [zodvik@gmail.com](mailto:zodvik@gmail.com)

## posts

<ul>
{% for post in site.posts %}
  <li>
  	<a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
