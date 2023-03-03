---
layout: default
---




![image]({{site.baseurl}}/img/JLS_round.png "image of J. Le Sommer"){:width="200px" style="float: left"}

<br>

I am **computational oceanographer**, interested in **cross-scale interactions** in the ocean and the climate system. I use and develop numerical tools to prepare the observations of **ocean dynamics from space**, to better understand its functioning and to improve its **representation in forecasting systems** and climate models.

<br>

## Interested in working with me ? 
Research appointments will be **considered at any time** for candidates with an outstanding profile. A number of schemes are available for funding **PhD** or **postdoctoral positions**. Interested applicants should contact me by email. 

## Recent posts
{% for post in site.posts limit:2%}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}



