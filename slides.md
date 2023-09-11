---
theme: default
colorSchema: dark
background: ./roller-coaster.jpg
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
hideInToc: true
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
hideInToc: true
---

# Table of contents

<Toc minDepth="1" maxDepth="5"></Toc>

---
layout: center
hideInToc: true
---

# Opens Source software consititute 70-90% of any given piece of modern software solution

<a href="https://www.linuxfoundation.org/blog/blog/a-summary-of-census-ii-open-source-software-application-libraries-the-world-depends-on">The Linux Foundation Open Source Software (FOSS)</a>

---
layout: center
hideInToc: true
---
# Faker.js

---
layout: center
hideInToc: true
---

<a href="https://www.theverge.com/2022/1/9/22874949/developer-corrupts-open-source-libraries-projects-affected">“Respectfully, I am no longer going to support Fortune 500s (and other smaller sized companies) with my free work”</a>

---
layout: center
transition: fade-out
---

# We have a responsibility to give something back

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
hideInToc: true
---

# What

A React UI Kit built on Google's official Material Components Web library
---
layout: center
hideInToc: true
---

# Why

* Based on <a href="https://github.com/material-components/material-components-web">Google Material Components for the Web</a>
* Avoids breaking changes (at all cost)
* Individually packaged and released components
* Not opinionated on e.g. styling
* How we would have done it on our own 😉

---
layout: center
---

# Alternatives

---
hideInToc: true
---

# Material UI or MUI

* Not based on Google Material Components for the Web
* Many breaking changes 💔
* Opinionated on styling etc.
* Today MUI has better traction than RMWC

---

# History

* Version 1 was released in January 2018
* Created by James Friedman
* Primarily a solo endeavor, truly remarkable
* Adopted by us in May 2018
* Today we have around 10 applications based on RMWC

---

# Abandonment

* Despite internal usage at Google, progress slowed down towards the end of 2020
* Not updated to latest version of Google Material Components for the Web
* Bugs weren't fixed
* Building our applications started to become problematic
* The community wasn't making significant contributions

---

<img src="discord.png" />

---
hideInToc: true
layout: center
---

# Options

---
hideInToc: true
---


# Migrate to MUI
* Large migrating effort
* Bad history of breaking changes
* Not a particular fun job to do

---
hideInToc: true
---

# Start contributing to RMWC
* Fun and exiting
* Might even be cheaper
* Our chance to contribute

---

# The friendly takeover part 1

* We got in contact with James around the beginning of 2022
* His ability to contribute to the project had diminished
* <a href="https://github.com/rmwc/rmwc/issues/758https://github.com/rmwc/rmwc/issues/758">Project Lazarus</a> was started to bring RMWC up to date

---
hideInToc: true
---

# The team

<div class="flex">
<div>
<img src="https://avatars.githubusercontent.com/u/975256?v=4" class="m-5 h-40 rounded shadow"/>
</div>
<div>
<img src="https://avatars.githubusercontent.com/u/12230809?v=4" class="m-5 h-40 rounded shadow"/>
</div>
<div>
<img src="https://avatars.githubusercontent.com/u/16644098?v=4" class="m-5 h-40 rounded shadow"/>
</div>
<div>
<img src="https://avatars.githubusercontent.com/u/1300390?v=4" class="m-5 h-40 rounded shadow"/>
</div>
<div>
<img src="https://avatars.githubusercontent.com/u/19765421?v=4" class="m-5 h-40 rounded shadow"/>
</div>
</div>

---
hideInToc: true
---

# What did we do?

* Weekly meetings
* Establish trust
* Defined a roadmap (Googler Material version 5 ➡ 8)
* Started working

----
# The friendly takeover part 2

* After a while, it became evident that James couldn't allocate the required time to invest in the project
* RMWC was change from a repo on James's profile into an Github organization
* We ended up with the keys to the kingdom 😨
* We are now working on releasing RMWC version 14 based on Google Material version 14

---

# Challenges

* Getting the needed time
* Corporate Windows setup
* Learning curve
* Yak shaving - toolchain and outdated dependencies

---

# Bennfits

* Fun and energizing
* Career enhancing
* Branding possibilities
* Control and independence

---
layout: center
---

<a href="https://github.com/rmwc/rmwc/graphs/contributors">
<img src="https://contrib.rocks/image?repo=rmwc/rmwc" />
</a>

---
layout: center
---

<img src="react-norway.jpg"/>

---
hideInToc: true
---

# Slides created with Slidev

[Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)
