---
layout: default
title: Reusable Om Components
---
### <span class="octicon octicon-link"></span> Reusable Components for Om written in ClojureScript

A place to share reusable om components. Pull requests welcome!

## Components

{% for category in site.categories %}
  <li><a name="{{ category | first }}">{{ category | first }}</a>
    <ul>
    {% for posts in category %}
      {% for post in posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    {% endfor %}
    </ul>
  </li>
{% endfor %}

### <span class="octicon octicon-link"></span> Who made this?

This is a side-project by [Petrus Theron](http://petrustheron.com/).
