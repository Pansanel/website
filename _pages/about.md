---
layout: page
permalink: /
title: About
nav: About
description: <a href="http://www.iphc.cnrs.fr/" class="page-description">Institut Pluridisciplinaire Hubert Curien</a> • <a href="https://www.cnrs.fr/" class="page-description">CNRS</a> • <a href="https://www.unistra.fr/" class="page-description">University of Strasbourg</a> 
address: <a href="https://goo.gl/maps/T5mvYxs4U3VvCpDC9" class="page-description">23, rue du Loess, 67000 Strasbourg, France</a>
---

<div class="col p-0 pt-4 pb-4">
  <h1 class="pb-3 title text-left font-weight-bold">Jérôme Pansanel</h1>
  <h6 class="m-0 mb-2" style="font-size: 0.83em;">{{ page.description }}</h6>
  {% if page.address %}
      <h6 class="m-0 mb-2" style="font-size: 0.83em;">{{ page.address }}</h6>
  {% endif %}
</div>

<article>
  <div class="profile float-right">
    <img class="img-fluid z-depth-1 rounded" src="{{ 'prof_pic.jpg' | prepend: '/assets/img/' | relative_url }} alt="A Photo that represents Jerome Pansanel" />
  </div>
  <div class="clearfix">
    <p>
      As research engineer at the <a href="http://www.iphc.cnrs.fr/">Hubert Curien Pluridisciplinary Institute</a>, I am leading the <a href="https://grand-est.fr">SCIGNE platform</a>, a facility dedicated to the management of large and complex scientific data collections.
    </p>

    <p>
      My activities focus on research and development in information technologies area:
    </p>

    <ul>
      <li>
        System administration (Grid and Cloud Computing, large storage system, ...) at SCIGNE
      </li>
      <li>
        Coordination of the technical activities at France Grilles
      </li>
      <li>
        Research on machine learning applied to computer system management.
      </li>
      <li>
        Promote research data best usage and data science at the University of Strasbourg
      </li>
      <li>
        Participation to the build of the European Open Science Cloud
      </li>
    </ul>

  <p>
    Several projects I am involved in are listed on the <a href="projects/">projects</a> page.
  </p>

  </div>

  <!-- News -->
  {% include news.html %}

</article>
