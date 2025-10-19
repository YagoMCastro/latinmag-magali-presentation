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
  
Magali: open software for inversion and analysis of magnetic microscopy data🧲🔬

</h1>
<p id="talk-authors">
  <a id="talk-speaker"><b>Yago Moreira Castro</b></a>,
  Leonardo Uieda,
  Gelson Ferreira de Souza-Junior
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

<div class="fragment text-left">

- Bellon et al. (2025) modeled vortex-state grains, a more realistic scenario, using micromagnetic simulations.
</div>
<div class="fragment text-left">

- <b>Hundreds to thousands</b> of vortex-state grains record a reliable TRM, indicating that the field was not ultra-weak.
</div>
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
<img src="assets/paper_1.png" style="width: 80%" >
<img src="assets/paper_2.png" style="width: 80%" >

===============================================================================
<img src="assets/example_unmixxing_components.png" style="width: 100%">

===============================================================================
<img src="assets/stereogram_unmixxing_components.png" style="width: 100%">

===============================================================================
# Needs
<div class="fragment text-left">

- Algorithms for **automatic detection** of magnetic **grains** and its **magnetic moment** determination

</div>
<div class="fragment text-left">

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
# Import standard Python libraries
import numpy as np
import skimage.exposure
import xarray as xr
import matplotlib.pyplot as plt
</span><span class="fragment">
# Import Fatiando a Terra libraries
import harmonica as hm
import ensaio
import magali
</span><span class="fragment">
# Download the data
fname = ensaio.fetch_morroco_speleothem_qdm(version=1, file_format="matlab")
data = magali.read_qdm_harvard(fname)
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
<pre class="compact"><code class="txt" data-trim data-noescape>
xarray.DataArray 'bz' (y: 600, x: 960)> Size: 5MB
array([[ 352.40587477,   94.8913792 ,   41.61924299, ...,  470.18833933,
         129.20055397,   18.50120941],
       [ 525.04809649,  624.84659897,   53.45418   , ...,  450.42515609,
         240.12455308,  -73.61367693],
       [ 105.0939369 ,  638.76559489,  307.60736872, ...,  236.91326522,
         386.8498122 ,  -86.44215589],
       ...,
       [ -83.74367957,   32.98078244, -411.75073652, ...,  745.99373583,
        1036.20033954, -140.64317643],
       [ 171.17113661, -214.47801235,  159.23437984, ...,  124.58138395,
         258.54331931,  -90.3376945 ],
       [  80.60950354,  273.08367487,  118.23499313, ...,   -4.19572521,
         -53.55728012,    2.10335918]])
Coordinates:
  * x        (x) float64 8kB 0.0 2.35 4.7 7.05 ... 2.249e+03 2.251e+03 2.254e+03
  * y        (y) float64 5kB 0.0 2.35 4.7 7.05 ... 1.403e+03 1.405e+03 1.408e+03
    z        (y, x) float64 5MB 5.0 5.0 5.0 5.0 5.0 5.0 ... 5.0 5.0 5.0 5.0 5.0
Attributes:
    long_name:  vertical magnetic field
    units:      nT
</code></pre>
</section>

===============================================================================
<!-- .slide: data-background-image="assets/qdm_data.png"  data-background-size="contain" data-background-color="#262626" -->

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
<span>
# Upward continuation
height_difference = 5.0 # μm
data_up = (
    hm.upward_continuation(data, height_difference)
    .assign_attrs(data.attrs)
    .assign_coords(x=data.x, y=data.y)
    .assign_coords(z=data.z + height_difference)
    .rename("bz")
)
</span>
</code></pre>
</section>

===============================================================================
<!-- .slide: data-background-image="assets/data_up.png"  data-background-size="contain" data-background-color="#262626" -->

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
<span>
# Calculate Total Gradient Amplitude (TGA)
dx, dy, dz, tga = magali.gradient(data_up)
data_up["dx"], data_up["dy"], data_up["dz"], data_up["tga"] = dx, dy, dz, tga
<span class="fragment">
# Stretch the contrast of TGA image
stretched = skimage.exposure.rescale_intensity(
    tga, in_range=tuple(np.percentile(tga, (1, 99)))
)
data_tga_stretched = xr.DataArray(stretched, coords=data_up.coords)
</span>
</code></pre>
</section>

===============================================================================
<!-- .slide: data-background-image="assets/stretched.png"  data-background-size="contain" data-background-color="#262626" -->

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
<span>
# Detect anomalies
bounding_boxes = magali.detect_anomalies(
    data_tga_stretched,
    size_range=[20, 150], # μm
    detection_threshold=0.02,
    border_exclusion=2,
)
</span>
</code></pre>
</section>

===============================================================================
<!-- .slide: data-background-image="assets/detection.png"  data-background-size="contain" data-background-color="#262626" -->

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
<span>
# Iterative nonlinear inversion
data_updated, locations_, dipole_moments_, r2_values = magali.iterative_nonlinear_inversion(
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
<span>
# Plot the data
</span><span class="fragment">
locations_arr = np.array(locations_)
</span><span class="fragment">
fig, ax = plt.subplots()
</span><span class="fragment">
data.plot.pcolormesh(ax=ax, cmap="seismic", vmin=-10000, vmax=10000)
</span><span class="fragment">
magali.plot_bounding_boxes(bounding_boxes, ax=ax, color="black", linewidth=1.5)
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

- <strong>Magali</strong> brings <b>automation, reproducibility</b>, and <b>speed</b> to these analyses

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

- Provide, discuss, and establish <b>data conventions</b> for magnetic microscopy
</div>
<div class="fragment text-left">

- Write functions to read data from <b>different microscope systems</b>
</div>
<div class="fragment text-left">

- Add more datasets to <b>Ensaio</b> for testing and <b>community use</b>
</div>
<div class="fragment text-left">

- Release <strong>Magali 1.0</strong> with improved docs and structure
</div>

===============================================================================
<!-- .slide: data-background-opacity="0.2" data-background-image="assets/magali-logo.png"  data-background-size="contain" data-background-color="#262626" -->
# Obrigado! ¡Gracias! Thank you!

<div class="row">
<div class="col">
<i class="fas fa-comments"></i>
<br>
Contact:
<a>yagomcastro1@gmail.com</a>

<i class="fab fa-github"></i>
<br>
Source code for this presentation:
<br>
[github.com/YagoMCastro/latinmag-magali-presentation](https://github.com/YagoMCastro/latinmag-magali-presentation)

<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
<br>
The contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
<div class="col">

[github.com/fatiando/magali](https://github.com/fatiando/magali)

<img src="assets/qr_magali.gif" style="width: 80%" >
</div>
</div>

<img src="assets/qr_magali.gif" style="width: 0%" >
<div class="r-stretch centered">
<div>

