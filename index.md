--- 
layout: default
title: Home
---

# Malou Agok Malou

I'm a computer science student who is persuing a Bachelor of Computer Science at RMIT University.

This site is my outlet to showcase my learning as i progress through my studies. 

I wanna learn to create data based applications that can help people make decisions in fields like sports and bio informatics. What started as an interest in football analytics has introduced me to machine learning models that can be used to identify cancer. 

## Posts 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%-d %B %Y" }}
    </li>
  {% endfor %}
</ul>