---
layout: page
title: Tech Wise Wisdom - One byte at a time!
tagline: JavaScript Node MongoDB CouchDB Angular Backbone Erlang Elixir 
---
{% include JB/setup %}
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



