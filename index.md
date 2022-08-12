---
layout: default
---



Welcome to my work homepage. Here's a relatively recent picture of me.

<img alt="A relatively recent headshot" src="DanGunter-pic-transp.png" width="150px">

## My current projects

{% comment %}
Add projects and their URLs here (until I figure out data)
{% endcomment %}
{% assign project_names = "IDAES, DISPATCHES, PARETO, NAWI/WaterTAP, TrustedCI, Wastewater Resilience" | split: ", " %}
{% assign project_homes = "idaes.org, idaes.org/dispatches, project-pareto.org, /www.nawihub.org/knowledge/watertap, www.trustedci.org" | split ", " %}

{% assign num = project_names.size %}
{% assign range = (1..num) %}
| Project | Links |
|:--------|:------|
{% for i in range %}
| {{project_names[i]}} | <a href="https://{{project_homes[i]}}"><img alt="Homepage" src="home-16px.png"></a> |
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


