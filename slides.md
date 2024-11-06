---
# You can also start simply with 'default'
theme: seriph
colorSchema: light
fonts: 
  sans: Vazirmatn

htmlAttrs:
  dir: rtl
  lang: fa

# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

# آشنایی بر نرم افزار وایرشارک

مقدمه ای بر نرم افزار های شنود ترافیک شبکه

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 inline-flex items-center rounded cursor-pointer" hover="bg-white bg-opacity-10">
  صفحه بعدی <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/ParsaJR/wireshark-presentation" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
transition: fade-out
layout: image-right
image: images/image.png
backgroundSize: 100% 100%
---

# آنالیز پکت یعنی چی؟{.heading}


<br>
فرآیند بررسی و تفسیر بسته های شبکه برای به دست آوردن بینش در مورد ترافیک شبکه(به هر منظوری)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<!--
Here is another comment.
-->

---
transition: slide-up
layout: full
level: 2
---
## نرم افزار های شنود ترافیک شبکه چطور کار میکنن؟ {.heading}

