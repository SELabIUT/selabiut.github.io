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
<div class="box">
  <span class="col-sm-2"><b>Title</b></span>
  <span class="col-sm-10">**{{ project.title }}**</span> <br/>

  <span class="col-sm-2"><b>Members</b></span>
  <span class="col-sm-10"> <em>{{ project.members }}</em></span> <br/>

  <span class="col-sm-2"><b>Description</b></span>
  <span class="col-sm-10"> {{ project.description }}</span> <br/>
  &nbsp;
</div>
{% endfor %}


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

div.box:hover {
  background-color: rgba(0,0,0,0.02);
  border-radius: 25px;
}


</style>
<br><br>