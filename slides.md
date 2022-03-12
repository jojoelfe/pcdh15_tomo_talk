---
theme: seriph
background: 
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ##  Imaging molecules in their native environment: cryo-electron tomography imaging of pcdh15 in mouse stereocilia

  Presentation slides 
drawings:
  persist: false
title:  Imaging molecules in their native environment - cryo-electron tomography imaging of pcdh15 in mouse stereocilia

---

#  Imaging molecules in their native environment
## Cryo-electron tomography imaging of Pcdh15 in mouse stereocilia

Johannes Elferich

<div class="abs-br m-6 flex gap-2">
  
  <a href="https://github.com/jojoelfe/pcdh15_tomo_talk" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Hair cells are the sensory cells for hearing, motion, and balance

<img src="/haircells.jpg" class="m-auto h-350px" />

<cite >Credit: Hair cells of inner ear. Dr David Furness</cite>

---

# What hair cells do

<stereocilia-animation></stereocilia-animation>

---

# The proteins underlying hair cell function

<div class="grid grid-cols-2  gap-x-2em gap-y-1em">
<img src="/components_cartoon.png" class="w-auto h-400px">

<img src="/components_render.png" class="w-auto h-400px">
<cite>Fettiplace</cite>
</div>

---

# PCDH15/LHFPL5 structure

<div class="flex">
<img src="/pcdh15_lhfpl5_cartoon.png" class="h-450px w-auto" />
<img src="/Cov_v1.png" class="h-450px w-auto">
<video controls muted loop id="myVideo2" class="w-auto h-200px">
  <source src="/Video 1.mov" type="video/mp4">
</video>
</div>

---

# Going in-situ

<div class="flex">
<img src="/approach.png" class="h-280px w-auto"/>
<img src="/mmm1.png" class="h-280px w-auto"/>
</div>

---

# Tomography

<div class="flex">
<img src="/Electron_Tomography.tif.jpg" class="w-auto h-400px"/>
<video controls muted loop id="myVideo2" class="w-auto h-400px">
  <source src="/tomo_ex.mp4" type="video/mp4">
</video>
<img src="/tomo_ex_xy.png" class="w-300px h-300px"/>
<img src="/tomo_ex_xz.png" class="w-300px h-300px"/>
<img src="/tomo_ex_zy.png" class="w-300px h-300px"/>

</div>


---

# Is this PCDH15?

<div class="flex">
<img src="/isthispcdh15.png" class="w-auto h-400px"/>
<img src="/meme.jpg" class="w-auto h-200px" />
</div>


---

# Labeling PCDH15 with antibodies - Try 1

<div class="flex">
<img src="/poly.png" class="w-auto h-400px" />
<img src="/g26.png" class="w-auto h-400px" />
<img src="/g27.png" class="w-auto h-400px" />

<img src="/slicer001.jpg" class="w-auto h-400px" />
<img src="/title.png" class="w-auto h-400px" />
</div>

---

# Labeling PCDH15 with antibodies - Try 2

<div class="grid grid-cols-3" >
<img src="/azubel.jpg">
<cite>Azubel, M., Carter, S. D., Weiszmann, J., Zhang, J., Jensen, G. J., Li, Y., & Kornberg, R. D. (2019). FGF21 trafficking in intact human cells revealed by cryo-electron tomography with gold nanoparticles. In eLife (Vol. 8). eLife Sciences Publications, Ltd. https://doi.org/10.7554/elife.43146 </cite>
</div>

---

# 39G7-AuNP binds as expected


<div class="flex">
<img src="/label_micrograph.png" />
<img src="/graph_we.png">
</div>

---

# Detection in-situ

<video autoplay muted loop id="myVideo">
  <source src="/labeled_movie.mp4" type="video/mp4">
</video>

---

# Two AuNP labels consistent with PCDH15 dimers

<video controls muted loop id="myVideo" class="h-450px">
  <source src="/Movie S2.mp4" type="video/mp4">
</video>

---

# Two AuNP labels consistent with PCDH15 dimers

<img src="/dimer.png" />

---

# One AuNP label - monomer? 

<img src="/monomer.png" />


---
# PCDH15 stoichiometry at the tip

---

# PCDH15 complexes - CDH23?

---

<div class="abs-bl w-full h-full">

<img src="/Figure_6.png" class="h-551px m-100px" />

</div>
---

# Summary + whats next

<ul>
<li>Immuno-AuNP allow cryo-EM imaging of rare protein complexes
<ul>
<li>Location</li>
<li>Stoichiometry</li>
<li>Conformation</li>
<li>Structure?</li>
</ul>
</li>

<li>Tip-links might occur in higher stoichiometries, similar to channels</li>
<li>PCDH15 and potentially CDH23 have predetermined bending points to adopt geometries required for trafficking</li>

<li>Detection of low-abundance and small proteins in cellular cryo-EM data remains challenging and an active area of research</li>
<li>Faster and more robust sample preparation techniques are critical</li>
</ul>
---

# Acknowledgments

---
# Learn More

