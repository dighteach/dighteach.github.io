---
title: COMP 488 & DIGH 402
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: Digital Humanities Design & Programming, Spring 2015
---

Welcome to the course website for COMP 488 & DIGH 402. 

This course is offered by the [Center for Textual Studies & Digital Humanities](http://www.luc.edu/ctsdh/) and the 
[Department of Computer Science](http://www.luc.edu/cs/) at [Loyola University Chicago](http://www.luc.edu).

***

#### Recent Updates
{% for post in site.posts limit: 5 %}
* {{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})

  {{ post.summary }}
{% endfor %}




