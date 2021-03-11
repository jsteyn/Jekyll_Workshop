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

{% for post in site.posts %}
- {{ post.date | date_to_string }}: [{{ post.title }}]({{ page.url | relative_url }}) by {{ post.author }}
{% endfor %}
