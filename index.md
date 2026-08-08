--- 
layout: default
title: Home
---

# Malou Agok Malou

I'm a student who is pursuing a Bachelor of Computer Science at RMIT University.

This site is my outlet to showcase my learning as i progress through my studies. 

I would like to create compelling data based applications that can help people make decisions in fields like sports and bio informatics / medicine / finance. What started as an interest in sports analytics has introduced me to machine learning and artificial intelligence. 

## Posts 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%-d %B %Y" }}
    </li>
  {% endfor %}
</ul>