---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About

{% for member in site.data.pi %}

<div class="jumbotron">
<div class="row">
<div class="col-sm-4">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" width="100%" style="max-width:250px"/>
</div>
<div class="col-sm-8 col-xs-12">
  <h3>{{ member.name (吕建伟)}}</h3>
  <h6><i>{{ member.info }}</i></h6>
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.ads %} <a href="{{ member.ads }}" target="_blank"><i class="ai ai-ads-square ai-3x"></i></a> {% endif %}
  {% if member.arxiv %} <a href="{{ member.arxiv }}" target="_blank"><i class="ai ai-arxiv-square ai-3x"></i></a> {% endif %}
  {% if member.orcid %} <a href="{{ member.orcid }}" target="_blank"><i class="ai ai-orcid-square ai-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %}

<div class="rowl3">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/UAlogo.png" class="img-responsive" width="10%" style="float: left; border-radius:1px; margin-right:10px; margin-top:10px; " />
  09/2014 - 03/2020, <strong>Doctor of Philosophy (Ph.D.)</strong> <br /> 
  Astronomy & Astrophysics, The University of Arizona <br /> 
  Supervisor: <a href="https://www.as.arizona.edu/people/faculty/george-h-rieke" target="_blank">Prof. George H. Rieke</a>, 
  <a href="https://repository.arizona.edu/handle/10150/636940" target="_blank"> Thesis Download </a> 
</p>
</div>

<div class="rowl3">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/SHAOlogo.png" class="img-responsive" width="10%" style="float: left; border-radius:1px; margin-right:10px;" />
  09/2011 - 06/2014, <strong>Master of Science (M.S.)</strong> <br /> 
  Shanghai Astronomical Observatory, CAS <br /> 
  </p>
</div>

<div class="rowl3">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/USTClogo.png" class="img-responsive" width="10%" style="float: left; border-radius:1px; margin-right:10px" />
  09/2007 - 06/2011, <strong>Bachelor of Science (B.S.)</strong> <br /> 
  The University of Science and Technology of China <br /> 
  </p>
</div>

</div>
</div>
</div>
{% endfor %}


<div class="jumbotron">
  <h3>Reserch Interest</h3>
  <ul>
      <li> extrgalactic survey and IR astronomy </li>
      <li> search and characterization of elusive AGN </li>
      <li> AGN IR properties and unification; interplay between the AGN torus and host ISM </li>
      <li> black hole/galaxy connection; high-z AGN and quasars </li>
      <li> optical and IR time-domain astronomy </li>
      <li> dust, PAH and star formation </li>
  </ul>
</div>




{% if site.data.people %}

<div class="jumbotron">
  <h3>Students and Mentoring</h3>
  <ul>
    {% for student in site.data.people %}
      <li>{{ student.name }}, {{ student.location }} ({{ student.degree }}, {{ student.year }})</li>
    {% endfor %}
  </ul>
</div>
{% endif %}

{% if site.data.funders %}

<div class="jumbotron">
  <h4>Sponsors</h4>
  <div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
  {% for funder in site.data.funders %}<a href="{{ funder.url }}" target="_blank"><img src='{{ site.url }}{{ site.baseurl }}/images/{{ funder.image }}' style='max-height: 80px; max-width: 200px; margin: 1%'/></a>{% endfor %}
  </div>
</div>
{% endif %}

