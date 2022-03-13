---
theme: ./theme
background: null
class: text-center
highlighter: shiki
lineNumbers: false
info: >
  ##  Imaging molecules in their native environment: cryo-electron tomography
  imaging of pcdh15 in mouse stereocilia


  Presentation slides 
drawings:
  persist: false
title: >-
  Imaging molecules in their native environment - cryo-electron tomography
  imaging of pcdh15 in mouse stereocilia
layout: intro
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

<img src="/haircells.jpg" class="m-auto h-430px" />

<cite class="ml-50px">Credit: Hair cells of inner ear. Dr David Furness</cite>

---

# How hair cells work

<stereocilia-animation></stereocilia-animation>

---

# The proteins underlying hair cell function

<div class="grid grid-cols-2  gap-x-2em gap-y-1em">
<img src="/components_cartoon.png" class="w-auto h-380px">

<img src="/components_render.png" class="w-auto h-380px">
<cite>Fettiplace R. Is TMC1 the Hair Cell Mechanotransducer Channel? Biophys J.
2016 Jul 12;111(1):3-9. </cite>
<cite>Holt JR, Tobin M, Elferich J, Gouaux E, Ballesteros A, Yan Z, Ahmed ZM, Nicolson T. Putting the Pieces Together: the Hair Cell Transduction Complex. J Assoc Res Otolaryngol. 2021 Dec;22(6):601-608</cite>
</div>

---

# PCDH15/LHFPL5 structure

<div class="flex">
<img src="/pcdh15_lhfpl5_cartoon.png" class="h-430px w-auto" />
<img src="/Cov_v1.png" class="h-430px w-auto">
<div class="w-400px" >
<video controls muted loop id="myVideo2" class="w-auto h-200px m-auto">
  <source src="/Video1.mp4" type="video/mp4">
</video>
<ul class="mt-20px">
<li>Are these conformational changes found <emph>in-situ</emph>?</li>
<li>Despite substantial efforts there is no structural data on any other components</li>
</ul>
<h3 class="mt-30px text-red-600">We have to look at the real thing!</h3>
</div>
</div>
<div class="ml-50px mt-10px">
<cite >Ge J*, Elferich J*, Goehring A, Zhao H, Schuck P, Gouaux E. Structure of mouse protocadherin 15 of the stereocilia tip link in complex with LHFPL5. Elife. 2018 Aug 2;7:e38770</cite>
</div>

---

# How to image stereocilia using cryo-EM

<div class="flex mt-100px">
<img src="/approach.png" class="h-280px w-auto"/>
<img src="/mmm1.png" class="h-280px w-auto ml-50px"/>
</div>

---

# Cryo-electron tomography

<div class="flex">
<img src="/Electron_Tomography.tif.jpg" class="w-auto h-430px"/>
<video controls muted loop id="myVideo2" class="w-auto h-430px">
  <source src="/tomo_ex.mp4" type="video/mp4">
</video>
<div class="grid grid-cols-2 ml-30px gap-y-0">
<img src="/tomo_ex_xy.png" class="w-200px h-200px"/>
<img src="/tomo_ex_zy.png" class="w-200px h-200px"/>

<img src="/tomo_ex_xz.png" class="w-200px h-200px"/>
</div>
</div>


---

# Identifying PCDH15

<div class="flex">
<img src="/isthispcdh15.png" class="w-auto h-400px"/>
<img src="/meme.jpg" class="w-auto h-200px ml-30px" />
</div>


---

# Labeling PCDH15 with antibodies - Try 1

<div class="flex flex-wrap">
<img src="/poly.png" class="w-auto h-200px" />
<img src="/g26.png" class="w-auto h-200px" />
<img src="/g27.png" class="w-auto h-200px" />

<img src="/slicer001.jpg" class="w-auto h-300px" />
<img src="/title.png" class="w-auto h-300px" />
</div>

---

# Labeling PCDH15 with antibodies - Try 2

<div class="grid grid-cols-3" >
<img src="/azubel.jpg" />
<img src="/trunc.png" />
<img src="/graphannot.png" />
<cite>Azubel, M., Carter, S. D., Weiszmann, J., Zhang, J., Jensen, G. J., Li, Y., & Kornberg, R. D. (2019). FGF21 trafficking in intact human cells revealed by cryo-electron tomography with gold nanoparticles. In eLife (Vol. 8). eLife Sciences Publications, Ltd. https://doi.org/10.7554/elife.43146 </cite>
</div>

---
layout: cover
background: /label_micrograph.png
---

# 39G7-AuNP binds as expected


<div class="flex">
<img src="/graph_we.png" class="abs-br m-10px h-150px p-10px" style="background-color:white;" > 
</div>


---
layout: cover
---



<video autoplay muted loop id="myVideo" class="abs-bl w-full -z-1" >
  <source src="/labeled_movie.mp4" type="video/mp4">
</video>

<div class="bg-gray-500/50 -ml-0.5rem pl-0.5rem  -mt-0.5rem rounded-1xl" style="display:table">
<h1 class="text-white m-0.5rem mb-0.5rem -ml-1rem">Detection in-situ</h1>
</div>

---

# Two AuNP labels consistent with PCDH15 dimers

<img src="/dimer.png" />

---

# One AuNP label - monomer? 

<img src="/monomer.png" />

---

# One AuNP label - monomer? 

<img src="/quant.png" class="mt-75px"/>

---

# PCDH15 numbers at the tip

<img src="/stoi.png" class="h-430px w-auto m-auto"/>

---

# PCDH15 complexes - CDH23?

<img src="/comp1.png" />

---

# PCDH15 complexes - CDH23?

<img src="/comp2_1.png" />
<img src="/comp2_2.png" />

---

<div class="abs-bl w-full h-full">

<img src="/Figure_6.png" class="h-551px ml-100px" />

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


<!--  ---

# Two AuNP labels consistent with PCDH15 dimers

<video controls muted loop id="myVideo" class="h-450px">
  <source src="/MovieS2.mp4" type="video/mp4">
</video>
-->
