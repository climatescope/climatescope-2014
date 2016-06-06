---
layout: page
title: Download
id: download
arrange: full
---

<ul class="well-list">

  <li>
    <div class="well well-l download download-pdf">
      <h2>Full Report</h2>
      <p>Download the full Climatescope 2014 report.</p>
      <ul class="download-list">
        <li>
          <a href="{{ site.domain }}{{ site.path_prefix }}/en/download/reports/climatescope-2014-report-en.pdf" title="Download full report in PDF" class="bttn bttn-success download data-download">PDF <span class="badge">19Mb</span></a>
        </li>
      </ul>
    </div>
  </li>

  <li>
    <div class="well well-l download download-data">
      <h2>Source Data</h2>
      <p>Download the complete set of underlying data.</p>
      <ul class="download-list">
        <li>
          <a href="{{ site.domain }}{{ site.path_prefix }}/en/download/data/climatescope-full.csv" title="Download Climatescope data in CSV format" class="bttn bttn-success download data-download">CSV <span class="badge">0.2Mb</span></a>
        </li>
        <li>
          <a href="{{ site.domain }}{{ site.path_prefix }}/en/download/model/climatescope-2014.xlsm" title="Download Climatescope model in Excel format" class="bttn bttn-success download data-download">Excel <span class="badge">5Mb</span></a>
        </li>
      </ul>
    </div>
  </li>

  <li>
    <div class="well well-l download download-pdf">
      <h2>Methodology</h2>
      <p>Download the full methodology used in the Climatescope 2014.</p>
      <ul class="download-list">
        <li>
          <a href="{{ site.domain }}{{ site.path_prefix }}/en/download/docs/climatescope-2014-methodology-en.pdf" title="Download methodology in PDF" class="bttn bttn-success download data-download">PDF <span class="badge">0.4Mb</span></a>
        </li>
      </ul>
    </div>
  </li>

</ul>

## Download by country

{% include download_table.html type='country' %}

## Download by state / province

{% include download_table.html type='state' %}