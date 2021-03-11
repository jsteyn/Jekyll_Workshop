---
layout: page
---

# About

## Project
{{ site.description }}

## Funders
We gratefully acknowledge funding from the XYZ Founding council, under grant number '123'.

## Team

{% for team_member in site.team_members %}
- **Name:** {{team_member.name }}, **role:** {{ team_member.role }}
{% endfor %}


## Cite us
You can cite the project as:

> *The Carpentries 2019 Annual Report. Zenodo. https://doi.org/10.5281/zenodo.3840372*
