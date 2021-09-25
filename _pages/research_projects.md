---
title: "SELab->Research"
layout: default
excerpt: "SELab -- Research"
sitemap: false
permalink: /research_projects/
---

<h2 style="font-family: 'Roboto', sans-serif; font-weight: 500; font-size: 32px;">Research Projects</h2>
<br>

<div id="projects_space">
{% for project in site.data.projects %}
<div class="col-sm-12">
  <p>
  **{{ project.title }}** <br/>
  <em>{{ project.members }} </em> </p>
  <p>{{ project.description }} </p><br/>
</div>
{% endfor %}
</div>


<br><br>
<style>
.container {
  height: 200px;
  position: relative;
  border: 3px solid green;
}

.vertical-center {
  margin: 0;
  position: absolute;
  top: 50%;
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
}

.box {
  display:inline-block;
  width:8px;
  height:8px;
  background-color: grey;
  margin-right:6px;
}
</style>
<br><br>