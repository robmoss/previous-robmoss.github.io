---
layout: site
title: Acute Renal Function Curves
js_libs: D3
---

<div class="charts morsel">
  <p>The following figures plot model simulation results against
    acute renal function curves obtained from experimental studies
    in the rat.
    This work was done in collaboration with S.&nbsp;Randall Thomas and
    has been
    <a href="http://dx.doi.org/10.1152/ajprenal.00089.2013">published</a> by
    <em>AJP Renal</em>.

  <p class="showjs"><strong>Instructions:</strong>
    Table 1 contains links to
    each publication's PubMed page, and allows the user to toggle the
    visibility of each experimental study on the plots below.</p>
  <p class="showjs">Hover the cursor over a line on either plot to
    identify the source of the data series; clicking on a line will keep
    that line selected, clicking on the tooltip will toggle whether the
    line will remain selected.</p>
  <p class="hidejs"><strong>Please enable javascript to view the
      plots.</strong></p>

  <span id="jna" class="chart"></span>
  <p class="caption">
    <strong>Figure 1:</strong> Regulation of sodium excretion.
  </p>

  <span id="jv" class="chart morsel"></span>
  <p class="caption">
    <strong>Figure 2:</strong> Regulation of water excretion.
  </p>
</div>

<!-- Generate the plots. -->
<script type="text/javascript" src="./plot.js" charset="utf-8"></script>
