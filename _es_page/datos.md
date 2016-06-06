---
layout: page
title : Descargas
id: download
arrange: full
---

<ul class="well-list">

  <li>
    <div class="well well-l download download-pdf">
      <h2>Informe regional</h2>
      <p>Descargar el informe del Climascopio 2014 sobre Latinoamérica y el Caribe.</p>
      <ul class="download-list">
        <li>
          <a href="{{ site.domain }}{{ site.path_prefix }}/es/download/reports/climatescope-2014-lac-es.pdf" title="Descargar el informe regional del Climascopio 2014 completo" class="bttn bttn-success download data-download">PDF <span class="badge">9.2Mb</span></a>
        </li>
      </ul>
    </div>
  </li>

  <li>
    <div class="well well-l download download-data">
      <h2>Datos</h2>
      <p>Descargar la totalidad de los datos subyacentes.</p>
      <ul class="download-list">
        <li>
          <a href="{{ site.domain }}{{ site.path_prefix }}/es/download/data/climatescope-full.csv" title="Descargar datos Climascopio en formato CSV" class="bttn bttn-success download data-download">CSV <span class="badge">0.2Mb</span></a>
        </li>
        <li>
          <a href="{{ site.domain }}{{ site.path_prefix }}/es/download/model/climatescope-2014.xlsm" title="Descargar datos Climascopio en formato Excel" class="bttn bttn-success download data-download">Excel <span class="badge">5Mb</span></a>
        </li>
      </ul>
    </div>
  </li>

  <li>
    <div class="well well-l download download-pdf">
      <h2>Metodologia</h2>
      <p>Descargar la metodología completa.</p>
      <ul class="download-list">
        <li>
          <a href="{{ site.domain }}{{ site.path_prefix }}/es/download/docs/climatescope-2014-methodology-es.pdf" title="Descargar metodologia en formato PDF" class="bttn bttn-success download data-download">PDF <span class="badge">0.4Mb</span></a>
        </li>
      </ul>
    </div>
  </li>

</ul>

## Descargar por país

{% include download_table.html type='country' %}

## Descargar por estado / provincia

{% include download_table.html type='state' %}