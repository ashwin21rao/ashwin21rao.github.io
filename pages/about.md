---
layout: page
title: About
permalink: /about/
weight: 2
---

# **About Me**

Hey! I am **{{ site.author.name }}** :wave:<br />
I'm a student at International Institute of Information Technology (IIIT)
Hyderabad, currently pursuing B.Tech in Computer Science and Engineering. I'm
interested in computer vision and its applications. I also play around with
machine learning. I love playing badminton and I'm a Red belt in Kung Fu!

<div class="row">
  {% include about/skills.html title="Programming Skills"
  source=site.data.programming-skills %} {% include about/skills.html
  title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">{% include about/timeline.html %}</div>
