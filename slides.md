---
theme: default
colorSchema: dark
background: https://lh3.googleusercontent.com/pw/AIL4fc9IcGYttFG1_ijz3BPLH4GB5Ebe3m_zm7K4naFGg_1TBMtUrH-Zs6PMF4OKS_msTdr3i3VAgCtipZ17J8HA9g929621UqaNaYKpvv3ILb8lFcXO-0UB4bh7UVVGHmIdYmLUC2jOjciAN9bj0ga229yC7A=w1401-h1051-s-no?authuser=0
highlighter: shikir
class: text-center
lineNumbers: false
info: |
  ## The open source rollercoaster

  The story of taking over a large Github project

  [RMWC takover](https://github.com/jensborch/rmwc-takeover)
drawings:
  persist: false
transition: slide-left
title: The open source rollercoaster
---

# The open source rollercoaster

The story of taking over a large Github project

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/jensborch/rmwc-takeover" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
transition: fade-out
---

# Table of contents

<Toc minDepth="1" maxDepth="5"></Toc>

---
layout: center
---

# Opens Source software consititute 70-90% of any given piece of modern software solution

<a href="https://www.linuxfoundation.org/blog/blog/a-summary-of-census-ii-open-source-software-application-libraries-the-world-depends-on">According to the The Linux Foundation Open Source Software (FOSS)</a>

---
layout: center
---

# We have a responsibility to give something back

---
layout: center
---
# Faker.js

<a href="https://www.theverge.com/2022/1/9/22874949/developer-corrupts-open-source-libraries-projects-affected">“Respectfully, I am no longer going to support Fortune 500s (and other smaller sized companies) with my free work”</a>

---
layout: center
---

# RMWC

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/rmwc/rmwc" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<style>
  .slidev-layout {
    .height: 100%;
    background-color: #6200ee;
  }
</style>

---
layout: center
---

# What

A React UI Kit built on Google's official Material Components Web library
---
layout: center
---

# Why

* Based on <a href="https://github.com/material-components/material-components-web">Google Material Components for the Web</a>
* Avoids breaking changes (at all cost)
* Individually packaged and released components
* Not opinionated on e.g. styling
* How we would have done it ourself

---
layout: center
---

# Alternatives

---

# Material UI or MUI

* Not based on Google Material Components for the Web
* Many breaking changes
* Opinionated on styling etc.
* Today MUI has better traction than RMWC

---

# History

* Version was 1 released January 2018
* Created by James Friedman
* Largely a one man effort - an astonishing achievement
* Adopted by us in May 2018
* Today we have around 10 applications based on RMWC

---

# Abandonment

* Progresses slowed at the end of 2020
* Weren't updated to latest version of Google Material Components for the Web
* Bugs weren't fixed
* Building our applications started to become problematic
* Even though the framework was used even by Google, others weren't contributing

---

# Options

* Migrate to MUI
  * Large migrating effort
  * Bad history of breaking changes
  * Not a particular fun job to do
* Start contributing to RMWC
  * Fun and exiting
  * Might even be cheaper
  * Our chance to contribute

---

# The friendly takeover

---
layout: center
---

<a href="https://github.com/rmwc/rmwc/graphs/contributors">
<img src="https://contrib.rocks/image?repo=rmwc/rmwc" />
</a>

---




# Slides created with Slidev

[Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)
