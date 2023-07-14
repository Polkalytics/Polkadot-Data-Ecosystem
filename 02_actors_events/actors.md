---
title: Actors
parent: Actors & Events
permalink: /actors_and_events/actors
layout: home
---

<ul>
{% for actor in site.actors %}
    <li><a href="{{ actor.url }}">{{ actor.title }}</a></li>
{% endfor %}
</ul>
