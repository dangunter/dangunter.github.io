---
layout: default
---

Welcome to my work homepage. Here's a relatively recent picture of me.

<img alt="A relatively recent headshot" src="DanGunter-pic-transp.png" width="150px">

## My current projects

| Project | Links |
|:--------|:------|
{% for project in site.data.projects %}
| {{ project.name }} | <a href="https://{{ project.home }}"><img alt="Homepage" src="home-16px.png"></a> 
 {% if project.github %}<a href="https:://github.com/{{ project.github }}"><img alt="GitHub" src="GitHub-Mark-16px.png">{% endif %}|
{% endfor %}

<!--
| IDAES   | <a href="https://idaes.org"><img alt="Homepage" src="home-16px.png"></a> <a href="https://github.com/idaes/idaes-pse"><img alt="GitHub" src="GitHub-Mark-16px.png"></a> |

* [DISPATCHES](https://idaes.org/dispatches) <a href="https://github.com/gmlc-dispatches/dispatches"><img alt="GitHub" src="GitHub-Mark-16px.png"></a>
* [PARETO](https://project-pareto.org) <a href="https://github.com/project-pareto"><img alt="GitHub" src="GitHub-Mark-16px.png"></a>
* [NAWI/WaterTAP](https://www.nawihub.org/knowledge/watertap/) <a href="https://github.com/watertap"><img alt="GitHub" src="GitHub-Mark-16px.png"></a>
* [TrustedCI](https://www.trustedci.org/)
* Wastewater Resilience
-->

My contact information:

> email: dkgunter at lbl dot gov  
> M/S 50B-2239  
> 1 Cyclotron Road  
> Berkeley, CA 94720  


