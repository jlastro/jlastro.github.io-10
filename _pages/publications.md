---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

For a complete list of publications, check NASA ADS, ORCID or Google Scholar.

<div class="container">
<div class="row">
<center>
<img src="{{ site.url }}{{ site.baseurl }}/images/word_cloud_2406.jpeg" width="80%"/><br/>
 <span style="font-size: 15px; color: yellow;">
Research Keyword Cloud </span> <br/>
</center>
</div>

== Featured publications:



<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

<div class="jumbotron">
### Refereed journal articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Refereed conference proceedings
{% bibliography --query @inproceedings %}
</div>
