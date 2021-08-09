### Lunar is a rolling-release, source-based Linux distribution for advanced users.

You begin by installing the _lunar core,_ a minimal command-line only system, with the tools to build the full experience you want.   
From there, you create your own customized system built entirely from source code.


<div class="flex flex-column flex-row-lt192 flex-wrap items-center justify-center bg-lunar-light lunar-dark pa2 mb2 w-75-l">
  <p class="measure-narrow pl4 order-2-landscape order-1-portrait">
  The release iso is known to be stable, and has been extensively tested. It will have older versions of <i>lunar core.</i>
  </p>
  <label for="dl-release-toggle"  class="order-1-landscape order-2-portrait w5 pv3 ph3 f3 link bg-animate bg-lunar-dark hover-bg-green lunar-light hover-white br1 tc w4 font-maven order-2">Release</label>
  <input type="checkbox" id="dl-release-toggle" class="dn">
    <div id="dl-release" class="flex flex-column-lt192 flex-row items-start justify-start order-3 pa2 lunar-dark">
        <a class="pa3 mh1 f3 link bg-animate bg-lunar-dark hover-bg-green lunar-light hover-near-white br1 tc w4 font-maven" href="#">64-bit</a>
        <a class="pa3 mh1 f3 link bg-animate bg-lunar-dark hover-bg-green lunar-light hover-near-white br1 tc w4 font-maven" href="#">32-bit</a>
    </div>
</div>

<div class="flex flex-column flex-row-ns flex-wrap items-center justify-center bg-lunar-dark lunar-light pa2 mb2 w-75-l">
  <p class="measure-narrow pl4 order-2-landscape order-1-portrait">
  The nightly iso has newer versions of our core programs, but has less quality testing and may not be as stable.
  </p>
  <button id="dl-release-toggle" class="order-1-landscape order-2-portrait w5 pv3 ph3 f3 link bg-animate bg-lunar-light hover-bg-green lunar-dark hover-white br1 tc w4 font-maven b--none order-2">Release</button>
    <div id="dl-release" class="flex flex-column-portrait flex-row-landscape items-start justify-start order-3 pa2">
        <a class="pa3 mh1 f3 link bg-animate bg-lunar-light hover-bg-green lunar-dark hover-near-white br1 tc w4 font-maven" href="#">64-bit</a>
        <a class="pa3 mh1 f3 link bg-animate bg-lunar-light hover-bg-green lunar-dark hover-near-white br1 tc w4 font-maven" href="#">32-bit</a>
    </div>
</div>
