---
layout: default
---

Welcome to my work homepage. Here's a relatively recent picture of me.

<img alt="A relatively recent headshot" src="DanGunter-pic-transp.png" width="150px">

## My current projects

| Project | Description | Links |
|:--------|:------------|:-----:|
{% for project in site.data.projects -%}
| {{ project.name }} | {{ project.desc }} | <a href="https://{{ project.home }}"><img alt="Homepage" src="home-16px.png"></a>
  {%- if project.github %}<a href="https:://github.com/{{ project.github }}"><img alt="GitHub" src="GitHub-Mark-16px.png">{% endif %}|
{% endfor %}

My contact information:

> email: dkgunter at lbl dot gov  
> M/S 50B-2239  
> 1 Cyclotron Road  
> Berkeley, CA 94720  


