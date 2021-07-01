---
layout: page
permalink: /publications/
title: publications 
years: [2021, 2020, 2019, 2018, 2017, 2016]
years_theses: [2019, 2014, 2013]
nav: true
---

[publications](/publications#publications) and [talks](/publications#talks) 

<h1 class="category">Publications</h1>
<span id="publications"></span>


<div class="publications">
<h4 class="category"> Conference papers and journal articles</h4>
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conf-papers -q @*[year={{y}}]* %}
{% endfor %}
</div>

<br>
<div class="publications">
<h4 class="category"> Book chapters</h4>
{% for y in page.years %}
  {% bibliography -f book-chapters -q @*[year={{y}}]* %}
{% endfor %}
</div>

<div class="publications">
<h4 class="category">Theses</h4>
{% for y in page.years_theses %}
  {% bibliography -f theses -q @*[year={{y}}]* %}
{% endfor %}
</div>

<div class="publications">
<h4 class="category">Non-archival stuff</h4>
{% for y in page.years %}
  {% bibliography -f non-archival -q @*[year={{y}}]* %}
{% endfor %}
</div>

<br>
<div class="talks">
<span id="talks"></span>
<h1 class="category">Talks</h1>

      <ul>
		  <li> Low-resource NLP: Lessons from Dependency Parsing. <a href="https://sigtyp.io/ws2021.html">Sigtyp 2021</a>, 10 June 2021. [<a href="https://www.youtube.com/watch?v=HrzrlhMnde0">video</a>|<a href="/assets/pdf/sigtyp21.pdf">slides</a>]
		  <li> Parsing Typologically Diverse Languages. Aix Marseille University, 26 Nov 2020.
		  <li> Parsing Typologically Diverse Languages. Workshop on <a href="https://tlt2020.phil.hhu.de/">Treebanks ang Linguistic Theories</a> (TLT), 27 October 2020. [<a href="https://t.co/937VFXcpPP">video</a>|<a href="/assets/pdf/tlt_2020_slides.pdf">slides</a>]
          <li> Do we need recursive subtree composition in dependency parsing? Invited talk at the Workshop on Data-driven Approaches to Parsing and Semantic Composition, Tübingen 10 December 2019. [<a href="/assets/pdf/tubingen1219.pdf">slides</a>]
