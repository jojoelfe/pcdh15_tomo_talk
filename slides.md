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

# Pcdh15/Lhfpl5 structure

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
<cite>Metlagel Z, Krey JF, Song J, Swift MF, Tivol WJ, Dumont RA, Thai J, Chang A, Seifikar H, Volkmann N, Hanein D, Barr-Gillespie PG, Auer M. Electron cryo-tomography of vestibular hair-cell stereocilia. J Struct Biol. 2019 May 1;206(2):149-155</cite>

---

# Cryo-electron tomography

<div class="flex">
<img src="/Electron_Tomography.tif.jpg" class="w-auto h-430px"/>
<video controls muted loop id="myVideo2" class="w-auto h-430px">
  <source src="/tomo_ex.mp4" type="video/mp4">
</video>
<div class="grid grid-cols-2 ml-30px gap-y-0 gap-x-5px">
<div>
<p class="text-center mt-0 mb-0">XY</p>
<img src="/tomo_ex_xy.png" class="w-200px h-200px"/>
</div>
<div>
<p class="text-center mt-0 mb-0">ZY</p>
<img src="/tomo_ex_zy.png" class="w-200px h-200px"/>
</div>
<div>
<p class="text-center mt-0 mb-0">XZ</p>
<img src="/tomo_ex_xz.png" class="w-200px h-200px"/>
</div>
</div>
</div>

<style>
p {
  margin-top: 0 !important;
  margin-bottom: 0.1rem !important;
}
</style>
---

# Technical details

<div class="grid grid-cols-2 gap-x-10px">
<div>
<h3>Microscope</h3>

- Titan Krios (Janelia and PNCC)
- Gatan BioQuantum energy filter
- Gatan K3 camera
- Operated using SerialEM

<h3>Parameters</h3>

- 1.7 Å/pix pixelsize
- 20 eV energy filter window
- Dose-symmetric tomogram acquistion at 3° intervals from -60° to +60°
- 120 e/Å total dose (~3 e/Å per exposure)
- 2-3.5 µm defocus

</div>

<div>
<h3>Data processing</h3>

- Motion correction using UCSF Motioncor2
- Tomogram processing using IMOD
- In case of substantial deformation final reconstruction with TomoAlign
- As necessary, tomograms were denoised using Topaz

</div>

</div>

---

# Identifying Pcdh15

<div class="flex">
<img src="/isthispcdh15.png" class="w-auto h-400px mt-40px"/>
<img src="/meme.jpg" class="w-auto h-200px ml-20px mt-140px" />
</div>


---

# Labeling Pcdh15 with antibodies - Polyclonal

<div class="grid grid-cols-2 justify-items-center gap-y-25px">
<img src="/poly.png" class="w-auto h-180px" />
<div class="flex">
<img src="/g26.png" class="w-auto h-180px" />
<img src="/g27.png" class="w-auto h-180px" />
</div>
<img src="/slicer001.jpg" class="w-auto h-250px" />
<img src="/title.png" class="w-auto h-250px" />
</div>

---

# Labeling Pcdh15 with antibodies - Monoclonal

<div class="grid grid-cols-3 gap-x-20px justify-items-center mt-50px" >
<img src="/azubel.jpg" />
<img src="/trunc.png" class="ml-50px"/>
<img src="/graphannot.png" class="ml--70px"/>

</div>

<div class="w-400px">
<cite >Azubel, M., Carter, S. D., Weiszmann, J., Zhang, J., Jensen, G. J., Li, Y., & Kornberg, R. D. (2019). FGF21 trafficking in intact human cells revealed by cryo-electron tomography with gold nanoparticles. In eLife (Vol. 8).  </cite>
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

# Two AuNP labels consistent with Pcdh15 dimers

<img src="/dimer.png" />

---

# One AuNP label - monomer? 

<img src="/monomer.png" />

---

# One AuNP label - monomer? 

<img src="/quant.png" class="mt-75px"/>

---

# Pcdh15 numbers at the tip

<img src="/stoi.png" class="h-430px w-auto m-auto"/>

---

# Pcdh15 complexes - Cdh23?

<img src="/comp1.png" class="mt-100px"/>

---

# Pcdh15 complexes - Cdh23?

<img src="/comp2_1.png" class="h-210px m-auto"/>
<img src="/comp2_2.png" class="h-210px mt-20px m-auto"/>

---

<div class="abs-bl w-full h-full">

<img src="/Figure_6.png" class="h-551px ml-100px" />

</div>
---

# Summary + whats next

<ul>
<li>Immuno-AuNPs allow cryo-EM imaging of rare protein complexes
<ul>
<li>Location</li>
<li>Numbers</li>
<li>Conformation</li>
<li>Structure?</li>
</ul>
</li>

<li>Tip-links might occur with more than one copy at the tip, similar to channels</li>
<li>Pcdh15 and potentially Cdh23 have predetermined bending points to adopt geometries required for trafficking</li>

<li>Detection of low-abundance and small proteins in cellular cryo-EM data remains challenging and an active area of research</li>
<li>Faster and more robust sample preparation techniques are critical</li>
</ul>
---

# Acknowledgments

<div class="grid grid-cols-3">
<div>
<p class="font-bold underline">Eric Gouaux</p>
<p class="font-bold">Sarah Clark</p>
<p class="font-bold">Jingpeng Ge</p>
<p class="font-bold">April Goehring</p>
<p class="font-bold">Aya Matsui</p>
<p>Makayla Freitas​</p>
<p>Prerana Gogoi​</p>
<p>Farzad Jalali-Yazdi</p>
<p>Junhoe Kim​</p>
<p>Vikas Navratna</p>
<p>Heidi Owen​</p>
<p>Prashant Rao​</p>
<p>Natalie Sheldon​</p>
<p>Chang Su​</p>
<p>Dongxue Yang​</p>
<p>Jie Yu​</p>
<p>Hongtao Zhu</p>
</div>
<div>
<p class="font-bold underline mt-2rem">Peter Barr-Gillespie</p>
<p>Jocelyn Krey</p>
<p class="font-bold underline mt-2rem">Theresa Nicholson</p>
<p class="font-bold underline mt-2rem">Pacific Northwest Cryo-EM Center:​</p>
<p>Claudia Lopez​​</p>
<p>Craig Yoshioka​​</p>
<p class="font-bold underline mt-2rem">Janelia Cryo-EM core:</p>
<p>Xiaowei Zhao</p>​
<p>Shixin Yang</p>​
<p class="font-bold underline mt-2rem">Other:​</p>
<p>Lauren-Ann Metskalis​​</p>
<p>Maia Azubel​</p>
</div>
<div>
<img src="https://www.hhmi.org/sites/default/files/Logos/JPG/HHMI-horizontal-signature-color.jpg" class="mt-360px" />
</div>
</div>

<style>
p {
font-size:1.2rem;
line-height:0.5rem !important;
 
}
  
</style>

---

# Learn More

<div class="grid grid-cols-4">

<paper-card title="Molecular structures and conformations of protocadherin-15
and its complexes on stereocilia elucidated by cryo-electron tomography"
authors="Johannes Elferich, Sarah Clark, Jingpeng Ge, April Goehring, Aya
Matsui, Eric Gouaux"
img_link="https://elifesciences.org/assets/patterns/img/patterns/organisms/elife-logo-xs.fd623d00.svg"
link="https://elifesciences.org/articles/74512"></paper-card>

<paper-card title="Structure of mouse protocadherin 15 of the stereocilia tip link in complex with LHFPL5"
authors="Jingpeng Ge, Johannes Elferich, April Goehring, Huaying Zhao, Peter Schuck, Eric Gouaux"
img_link="https://elifesciences.org/assets/patterns/img/patterns/organisms/elife-logo-xs.fd623d00.svg"
link="https://elifesciences.org/articles/38770"></paper-card>

<paper-card title="FGF21 trafficking in intact human cells revealed by cryo-electron tomography with gold nanoparticles"
authors="Maia Azubel, Stephen D Carter, Jennifer Weiszmann, Jun Zhang, Grant J Jensen, Yang Li, Roger D Kornberg"
img_link="https://elifesciences.org/assets/patterns/img/patterns/organisms/elife-logo-xs.fd623d00.svg"
link="https://elifesciences.org/articles/43146"></paper-card>

<paper-card title="Electron cryo-tomography of vestibular hair-cell stereocilia"
authors="Zoltan Metlagel, Jocelyn F Krey, Junha Song, Mark F Swift, William J Tivol, Rachel A Dumont, Jasmine Thai, Alex Chang, Helia Seifikar, Niels Volkmann, Dorit Hanein, Peter G Barr-Gillespie, Manfred Auer"
img_link="https://www.ncbi.nlm.nih.gov/corehtml/pmc/pmcgifs/logo-jbsx.gif"
link="https://www.sciencedirect.com/science/article/abs/pii/S1047847719300292?via%3Dihub"></paper-card>

</div>

<style>
a {
border-style: none !important;
 
}
  
</style>