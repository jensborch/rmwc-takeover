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
layout: center
---

# Table of contents

<Toc minDepth="1" maxDepth="5"></Toc>

---
layout: center
hideInToc: true
---

# Opens Source software consititute 70-90% of any given piece of modern software solution

<a href="https://www.linuxfoundation.org/blog/blog/a-summary-of-census-ii-open-source-software-application-libraries-the-world-depends-on">The Linux Foundation Open Source Software (FOSS)</a>

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
hideInToc: true
---
# Faker.js
<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
hideInToc: true
---

<a href="https://www.theverge.com/2022/1/9/22874949/developer-corrupts-open-source-libraries-projects-affected">“Respectfully, I am no longer going to support Fortune 500s (and other smaller sized companies) with my free work”</a>

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---

<img  src="fakerjs-scandal.png" class="m-5 h-100"/>

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
transition: fade-out
---

# We have a responsibility to give something back

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---

<img  src="rmwc.svg" class="m-5 h-100"/>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/rmwc/rmwc" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
hideInToc: true
---

# What

A React UI Kit built on Google's official Material Components Web library

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: iframe
url: https://rmwc.io
---

---
layout: center
hideInToc: true
---

# Why

* Based on <a href="https://github.com/material-components/material-components-web">Google Material Components for the Web</a>
* Avoids breaking changes (at all cost)
* Individually packaged and released components
* Not opinionated on e.g. styling
* Accessible
* How we would have done it on our own 😉

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---

# Alternatives

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
hideInToc: true
---

# Material UI or MUI

* Not based on Google Material Components for the Web
* Many breaking changes 💔
* Opinionated on styling etc.
* Today MUI has better traction than RMWC

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---
# The takeover timeline

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---
# History

* Version 1 was released in January 2018
* Created by James Friedman
* Primarily a solo endeavor, truly remarkable
* Adopted by us in May 2018
* Today we have around 10 applications based on RMWC

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---
# Abandonment

* Despite internal usage at Google, progress slowed down towards the end of 2020
* Not updated to latest version of Google Material Components for the Web
* Bugs weren't fixed
* Building our applications started to become problematic
* The community wasn't making significant contributions

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---

```mermaid {theme: 'neutral', scale: 0.8}
graph TD
A{{Your project}}
A -->|depends on| B[miragejs v1] --> |depends on| C[fakerjs v1]
A -->|depends on| D[fakerjs v2] 
```

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---
<img src="discord.png" />

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
hideInToc: true
layout: center
---

# Options

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
hideInToc: true
layout: center
---


# Migrate to MUI
* Large effort
* Big bang migration or double maintenance
* Bad history of breaking changes
* Not a particular fun job to do

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
hideInToc: true
layout: center
---

# Start contributing to RMWC
* Fun and exiting
* Might even be cheaper
* Our chance to contribute

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---
# The friendly takeover part 1

* We got in contact with James around the beginning of 2022
* His ability to contribute to the project had diminished
* <a href="https://github.com/rmwc/rmwc/issues/758https://github.com/rmwc/rmwc/issues/758">Project Lazarus</a> was started to bring RMWC up to date

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
hideInToc: true
layout: center
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

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
hideInToc: true
layout: center
---

# What did we do?

* Weekly meetings
* Establish trust
* Defined a roadmap (Googler Material version 5 ➡ 8)
* Started working

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---
# The friendly takeover part 2

* After a while, it became evident that James couldn't allocate the required time to invest in the project
* RMWC was changed from a repo on James's profile into an Github organization
* We ended up with the keys to the kingdom 😨🔑
* We are now working on releasing RMWC version 14 based on Google Material version 14

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---

# Challenges

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
hideInToc: true
---

# Getting the needed time
* Management was positive
* Initial work done as part of maintenance
* Front-end organization scaling

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
hideInToc: true
---
# Yak shaving ✂💈
Yak shaving is programming lingo for the seemingly endless series of small tasks that have to be completed before the next step in a project can move forward.

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
hideInToc: true
---
# Other challenges
* Corporate Windows setup (🍏❤)
* Learning curve 📈

<img src="jens.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---
# Benefits

* Fun and energizing ⚡
* Career enhancing
* Branding possibilities
* Control and independence
* Active GitHub profile

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---

<img src="github-looks-like-this.png">

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---

<img src="bjarne.png">

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---

<a href="https://github.com/rmwc/rmwc/graphs/contributors">
<img src="https://contrib.rocks/image?repo=rmwc/rmwc" />
</a>

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
layout: center
---

<img src="react-norway.jpg"/>

<img src="emilie.png" alt="Image" class="absolute right-5 bottom-5 w-20 h-20 rounded-full">

---
hideInToc: true
layout: center
---

# Slides created with Slidev

[Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)
