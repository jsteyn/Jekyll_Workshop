---
lesson-example: "https://carpentries.github.io/lesson-example/ "
layout: default
title: "Learning how to build websites with Jekyll"
---

## Description ##

{{ site.description }}

{% assign lead = site.team_members | where:"role", "project lead" | first %}
The project is lead by {{ lead.name }}.
[See our full team](about).


More details about the project are available from [About Page](about.md)

See some [examples of our work]({{ page.lesson-example }})

## Blog Posts

{% for posts in site.posts %}
- {{ posts.date | date_to_string }}: {{ posts.title }}
{% endfor %}
