---
title: "SELab->Members"
layout: gridlay
excerpt: "SELab -- Members"
sitemap: false
permalink: /members/
---

<h2 style="font-family: 'Roboto', sans-serif; font-weight: 500; font-size: 32px;">Head of SELab</h2>
<br>
<div class="row">
  <div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/group-members/faculty/Shohel-Ahmed.png" class="img-responsive" width="80%" style="float: center" />
  <br>
  <h4><a href="http://www.iit.du.ac.bd/about_iit/individual_teacher/47">Shohel Ahmed</a></h4>
  Assistant Professor<br>
  Islamic University of Technology<br>
  <i><a.shohel@iut-dhaka.edu></i><br>
  BSc(IUT)<br>
  Former Software Engineer<br>
  Samsung R&D Ltd, BD<br>
  </div>
  <div class="col-sm-9"> 
  <p align="justify">
Shohel Ahmed is working as an Assistant Professor at the Department of Computer Science and Engineering, Islamic University of Technology, Bangladesh. He served as a faculty member of Sylhet International University, Bangladesh for 6 years. Later he joined Samsung R&D Institute Bangladesh (SRBD) as Technical Lead. There he served almost 5 years and left the company as a Chief Engineer. He also worked at Kona Software Lab Ltd. as Seniorr Project Manager
for 2.5 years. He has received M.Sc from the Computer Science and Engineering, INHA University, South Korea in 2009. He has completed B.Sc. in Computer Science & Information Technology from Islamic University of Technology
Bangladesh. His research interests Software Engineering, network analysis etc.
</p> </div>
</div>



<h2 style="font-family: 'Roboto', sans-serif; font-weight: 500; font-size: 32px;">Faculty Members</h2>
<br>

{% assign number_printed = 0 %}
{% for member in site.data.teachers %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/group-members/faculty/{{ member.photo }}"  width="128px" height="128px" style="float: left" />
  <h4><a href="{{ member.homepage }}" target="_blank">{{ member.name }}</a></h4>
  <i><b>{{ member.current_position }}</b></i> <br>
  <i><b>{{ member.current_organization }}</b></i> <br>
  <i>email: {{ member.email }}</i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}



<h2 style="font-family: 'Roboto', sans-serif; font-weight: 500; font-size: 32px;">Members</h2>
<br>

{% assign number_printed = 0 %}
{% for member in site.data.members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/group-members/current_members/{{ member.photo }}"  width="128px" height="128px" style="float: left" />
  <h4><a href="{{ member.homepage }}" target="_blank">{{ member.name }}</a></h4>
  <i>{{ member.current_position }} </i> <br>
  <i>{{ member.student_id }} </i> <br>
  <i>email: {{ member.email }}</i>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}



<h2 style="font-family: 'Roboto', sans-serif; font-weight: 500; font-size: 32px;">Alumni</h2>
<br>

{% assign number_printed = 0 %}
{% for member in site.data.alumni %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/group-members/alumni/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4><a href="{{ member.homepage }}" target="_blank">{{ member.name }}</a></h4>
  <i>{{ member.current_position }} </i> <br>
  <i>{{ member.current_organization }} </i> <br>
  <i>email: {{ member.email }}</i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br/>
### Administrative Support
If you need to update your information, feel free to contact <a href="mailto:jubair@iut-dhaka.edu" target="_blank">Md. Jubair Ibna Mostafa</a>.

<style>
  @media (max-width: 420px) {.fa-ul::before{content: "\A";white-space: pre;}}
</style>