<!--
-------------------------------------------------------------------------------
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-------------------------------------------------------------------------------
-->

<!-- .slide: class="slide-title" data-background-opacity="0.3" data-background-image="assets/magali-logo.svg" data-background-color="#000000" data-background-size="contain" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<h1 id="talk-title">
  
  Open-source solutions for the magnetic microscopy comunity 🧲🔬

</h1>
<p id="talk-authors">
  <a id="talk-speaker">Yago M Castro</a>
</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="row talk-info">
<div class="col-large">

<i class="fa fa-calendar-alt" style="margin: 0 10px 0 0"></i>
20 of October 2025
<span style="margin: 0 20px"></span>
$8^{th}$ Biennial LATINMAG Meeting | Morelia, Mexico

<!-- Permission to reuse and CC-BY license logo -->
<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Feel free to screenshot/share/reuse this presentation
<span style="margin: 0 20px"></span>
<a href="https://creativecommons.org/licenses/by/4.0/"><i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>CC-BY 4.0 License</a>

</div>
<div class="col-medium">

<!-- Add logos here. Need these wrappers to align them to the bottom right -->
<div class="talk-logos-container">
<div class="talk-logos">
  <a href="https://www.compgeolab.org"><img src="assets/compgeolab-banner-light.svg" alt="Computer-Oriented Geoscience Lab"></a>
  <a href="https://www.iag.usp.br/"><img src="assets/iag.png" alt="Instituto de Astronomia, Geofísica e Ciências Atmosféricas"></a>
  <a href="https://www.iag.usp.br/"><img src="assets/latinmag_logo.jpg" alt="Logo LATINMAG"></a>
  <!-- <a href="https://www.usp.br/"><img src="assets/usp.png" alt="Universidade de São Paulo"></a> -->
</div>
</div>

</div>
</div>

===============================================================================
<div class="r-stretch">
  <img src="assets/sample.svg" height=100%>
</div>

===============================================================================
<div class="r-stretch">
  <img src="assets/arrow.svg" height=100%>
</div>

===============================================================================
<div class="r-stretch">

  <img src="assets/qdm.jpg" height=115%>

</div>
<br>
<div class="footnote-left">

[Harvard Paleomagnetics Lab](https://paleomag.fas.harvard.edu/laboratory)
</div>

===============================================================================
<!-- .slide: class="slide-title" data-background-opacity="1" data-background-image="assets/ceramic.png"  data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote-center">

[Souza-Junior et al 2024](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023GC011082)
</div>

===============================================================================

<img src="assets/berndt_paper.png" style="width: 80%" >

===============================================================================

<img src="assets/bellon_paper.png" style="width: 80%" >

===============================================================================

<h1>Revisiting the Assumptions</h1>

<ul>
  <li class="fragment"><b>Bellon et al. (2025)</b> tested more realistic, <b>non-equidimensional grains</b> using micromagnetic modeling</li>
  <li class="fragment">Found that <b>grain morphology stabilizes magnetization</b> even within the “magnetically unstable zone”</li>
  <li class="fragment">Assemblages of only <b>tens to hundreds of grains</b> can produce a coherent TRM direction</li>
</ul>

<div class="footnote-left">

[Bellon et al. (2025)](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2025GL114771)
</div>

===============================================================================
<img src="assets/bellon_result_1.png" style="width: 100%">

===============================================================================
<img src="assets/bellon_result_2.png" style="width: 100%">

===============================================================================
<img src="assets/bellon_result_3.png" style="width: 100%">

===============================================================================
<img src="assets/bellon_result_4.png" style="width: 100%">

===============================================================================

<!-- .slide: class="slide-title" data-background-opacity="1" data-background-image="assets/real_data.png"  data-background-size="contain" -->

===============================================================================
<img src="assets/angular_misfit_basalt_vs_ceramic.png" style="width: 100%">

===============================================================================
# Needs
<div>

- Algorithms for **automatic detection** of magnetic **grains** and its **magnetic moment** determination

</div>

===============================================================================
<img src="assets/paper_1.png" style="width: 80%" >
<img src="assets/paper_2.png" style="width: 80%" >

===============================================================================
# Needs
<div >

- Algorithms for **automatic detection** of magnetic **grains** and its **magnetic moment** determination

</div>
<div class="fragment">

- **Open software** for forward **modelling** and **inversion** techniques specific to magnetic microscopy 

</div>

<div class="fragment text-left">

- **Data conventions**  

</div>

===============================================================================
<!-- .slide: data-background-opacity="1" data-background-image="assets/readme-banner.png"  data-background-size="contain" data-background-color="#262626" -->

===============================================================================
<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->

<div class="huge ">

What is Magali?

<div class="large fragment">

Free and open source 
<br>
<i class="fab fa-github"></i> <i class="fas fa-lock-open"></i>  <i class="fab fa-osi"></i>

</div>

</div>
<div class="large fragment">

Python library <i class="fab fa-python"></i>

</div>

<div class="large fragment">

Modelling and processing magnetic microscopy data 
<br>
<i class="fas fa-magnet"></i> <i class="fas fa-microscope"></i>

</div>

===============================================================================
<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->
# Why do we want to make it?

<div class="fragment text-left">

- Provide code that is **easy to use**

</div>

<div class="fragment text-left">

- Determine the **spatial positions** of **multiple** grains

</div>
<div class="fragment text-left">

- Facilitate the creation of **synthetic data**

</div>
<div class="fragment text-left">

- Propose a standard **data format**

</div>

<div class="fragment text-left">

- Serve as a **foundation** for new methods 

</div>
<div class="fragment text-left">

- Leverage the potential of emerging **magnetic microscopy** studies

</div>

===============================================================================
<section>
<style>
  pre.compact code {
    line-height: 1.0em !important;
    font-size: 1.3em !important;
  }
  .fragment {
    display: block;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
  }
  .block-space {
    margin-top: -1.0em !important;
  }
</style>
<pre class="compact"><code class="python" data-trim data-noescape>
<span class="fragment">
import numpy as np
import magali as mg
import harmonica as hm
import skimage.exposure
import xarray as xr
import matplotlib.pyplot as plt
import ensaio
</span><span class="fragment">
fname = ensaio.fetch_morroco_speleothem_qdm(version=1, file_format="matlab")
data = mg.read_qdm_harvard(fname)
</span><span class="fragment">
height_difference = 5.0
data_up = (
    hm.upward_continuation(data, height_difference)
    .assign_attrs(data.attrs)
    .assign_coords(x=data.x, y=data.y)
    .assign_coords(z=data.z + height_difference)
    .rename("bz")
)
</span><span class="fragment">
dx, dy, dz, tga = mg.gradient(data_up)
data_up["dx"], data_up["dy"], data_up["dz"], data_up["tga"] = dx, dy, dz, tga
</code></pre>
</section>

===============================================================================
<section>
<style>
  pre.compact code {
    line-height: 1.0em !important;
    font-size: 1.3em !important;
  }
  .fragment {
    display: block;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
  }
  .block-space {
    margin-top: -1.0em !important;
  }
</style>
<pre class="compact"><code class="python" data-trim data-noescape>
</span><span>
stretched = skimage.exposure.rescale_intensity(
    tga, in_range=tuple(np.percentile(tga, (1, 99)))
)
data_tga_stretched = xr.DataArray(stretched, coords=data_up.coords)
</span>
</span><span class="fragment">
bounding_boxes = mg.detect_anomalies(
    data_tga_stretched,
    size_range=[30, 50],
    detection_threshold=0.07,
    border_exclusion=2,
)
</span><span class="fragment">
data_updated, locations_, dipole_moments_, r2_values = mg.iterative_nonlinear_inversion(
    data_up,
    bounding_boxes,
    height_difference=height_difference,
    copy_data=True,
)
</span>
</code></pre>
</section>

===============================================================================
<section>
<style>
  pre.compact code {
    line-height: 1.0em !important;
    font-size: 1.3em !important;
  }
  .fragment {
    display: block;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
  }
  .block-space {
    margin-top: -1.0em !important;
  }
</style>
<pre class="compact"><code class="python" data-trim data-noescape>
</span><span>
locations_arr = np.array(locations_)
</span><span class="fragment">
fig, ax = plt.subplots()
</span><span class="fragment">
data.plot.pcolormesh(ax=ax, cmap="seismic", vmin=-5000, vmax=5000)
</span><span class="fragment">
mg.plot_bounding_boxes(bounding_boxes, ax=ax, color="black", linewidth=1.5)
</span><span class="fragment">
ax.scatter(
    locations_arr[:, 0],  # x
    locations_arr[:, 1],  # y
    c="green",
    marker=".",
    s=60,
    label="Dipole estimated location"
)
plt.legend()
</span><span class="fragment">
plt.show()
</span>
</code></pre>
</section>

===============================================================================
<!-- .slide: data-background-opacity="1" data-background-image="assets/magali_code_example.png"  data-background-size="contain" data-background-color="#262626" -->

===============================================================================
# Conclusions
<div class="fragment text-left">

- Magnetic microscopy lets us investigate magnetism at the grain scale
</div>
<div class="fragment text-left">

- <strong>Magali</strong> brings automation, reproducibility, and speed to these analyses

</div>
<style>
  .fragment .inline{
    display: inline !important;
  }
</style>
<div class="fragment text-left">

  - <span class="inline">It integrates open tools,</span>
</div>


===============================================================================
# Conclusions
<div class="text-left">

- Magnetic microscopy lets us investigate magnetism at the grain scale
</div>
<div class="text-left">

- <strong>Magali</strong> brings automation, reproducibility, and speed to these analyses

</div>
<style>
  .fragment .inline{
    display: inline !important;
  }
</style>

<div class="text-left">

  - <span class="inline">It integrates open tools,</span><span class="inline"> FAIR data,</span>
</div>
<div class="footnote-center">

<b>FAIR</b>: <b>F</b>indable, <b>A</b>ccessible, <b>I</b>nteroperable and <b>R</b>eusable</div>

</div>


===============================================================================
# Conclusions
<div class="text-left">

- Magnetic microscopy lets us investigate magnetism at the grain scale
</div>
<div class="text-left">

- <strong>Magali</strong> brings automation, reproducibility, and speed to these analyses

</div>
<style>
  .fragment .inline{
    display: inline !important;
  }
</style>

<div class="text-left">

- It integrates open tools, FAIR data, and transparent workflows for magnetic research
</div>


===============================================================================
# Future work
<div class="fragment text-left">

- Provide, discuss, and establish data conventions for magnetic microscopy
</div>
<div class="fragment text-left">

- Write functions to read data from different microscope systems
</div>
<div class="fragment text-left">

- Add more datasets to <strong>Ensaio</strong> for testing and community use
</div>
<div class="fragment text-left">

- Release <strong>Magali 1.0</strong> with improved docs and structure
</div>

===============================================================================
<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->
<div class="r-stretch centered">
<div>

<i class="fas fa-comments"></i>
<br>
Contact:
<a>yagomcastro1@gmail.com</a>

<i class="fab fa-github"></i>
<br>
Source code for this presentation:
<br>
[https://yagomcastro.github.io/magali-msc-qualification/](https://github.com/YagoMCastro/magali-msc-qualification)

<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
<br>
Unless otherwise noted,
the contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
</div>