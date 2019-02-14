---
layout: default
title: Home
---

# hi!

I'm Nikhil, a software engineer based in India. I am an early adoptor and like to run things when they are in beta.

I keep a running page to [bookmark] articles, books & videos that I recommend.

You can reach me at [zodvik@gmail.com](mailto:zodvik@gmail.com)

## posts

<ul>
{% for post in site.posts %}
  <li>
  	<a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

## purchases

<ul>
{% for post in site.purchases %}
  <li>
  	<a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>


## drafts

<ul>
{% for post in site.drafts %}
  <li>
  	{{ post.title }}
  </li>
{% endfor %}
</ul>

[bookmark]: /bookmarks