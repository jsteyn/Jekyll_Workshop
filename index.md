---
lesson-example: "https://carpentries.github.io/lesson-example/ "
layout: default
title: "Learning how to build websites with Jekyll"
---

## Description ##

{{ site.description }}

{% assign lead = site.team_members | where:"role", "project lead" | first %}


More details about the project are available from [About Page](about.md)

See some [examples of our work]({{ page.lesson-example }})
