---
layout: page
title: Meetings
---

<p class="message">
  The quant-crim group meet once a month, usually on a Wednesday afternoon. This page contains some of the minutes and presentations from our meetings.
</p>

<p>If you would like to be added to the list, please email <a href="http://www.geog.leeds.ac.uk/people/n.malleson/">Nick Malleson</a></p>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
