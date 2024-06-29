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

For a complete list of publications, check
<a href="https://arxiv.org/search/advanced?advanced=1&terms-0-operator=AND&terms-0-term=jianwei+lyu&terms-0-field=author&classification-physics=y&classification-physics_archives=astro-ph&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first"><button class="btn-doi"><i class="ai ai-arxiv" aria-hidden="true"></i> ArXiv </button></a>, 
<a href="https://ui.adsabs.harvard.edu/public-libraries/jbbTsn0iQhuruu2S8X9e3Q"><button class="btn-abstract"><i class="ai ai-ads" aria-hidden="true"></i> NASA ADS </button></a>, 
<a href="https://orcid.org/0000-0002-6221-1829"><button class="btn-bib"><i class="ai ai-orcid" aria-hidden="true"></i> ORCID </button></a>, or
<a href="https://scholar.google.com/citations?user=OHejMf0AAAAJ&hl=en"><button class="btn-arxiv"><i class="ai ai-google-scholar" aria-hidden="true"></i> Google Scholar </button></a>.

<div class="container">
<div class="row">
<center>
<img src="{{ site.url }}{{ site.baseurl }}/images/word_cloud_2406.jpeg" width="60%"/><br/>
 <span style="font-size: 15px; color: yellow;">
Research Keyword Cloud </span> <br/>
</center>
</div>

### Featured publications:



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
