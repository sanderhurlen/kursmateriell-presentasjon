---
theme: apple-basic
layout: image-right
image: "https://www.skatteetaten.no/static/img/skatteetatenlogo/1200x630/png/se_logo_norsk_sort1200x630.png"

# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Presentasjon til react-workshop

# persist drawings in exports and build
drawings:
  persist: false
---
# Kom i gang med webutvikling

Skatteetaten

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    La oss starte <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/sanderhurlen/kursmateriell-kvist" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!-- Notater til intro-->
---
src: ./slides/agenda.md
---

<!-- DEL 2 - Presentasjon av skatteetaten -->

---
src: ./slides/om-skatteetaten/intro.md
---


<!-- DEL 3 - Workshop -->
---
layout: section
---

# Del 3: Workshop

---
layout: image-right
image: https://reactjs.org/logo-og.png
---

# Del 3: Workshop

### Hva vi skal lære i dag

- 👨🏼‍🚀 JavaScript-verdenen og React
- 🪝 Hooks og komponenter
- 📄 Single Page Application

* (ved tid) 🧪 Komme i gang med testing

<!--
I dette kurset skal vi fokusere på de grunnleggende ferdighetene som behøves for å komme i gang med webutvikling generelt, men med React som vi skal lære om i dag. I utgangspunktet ser ikke dette ut som mye. Men tro meg, det er utrolig mye spennende vi skal sette oss inn i. Noen av dere har helt sikkert sett videoer av noe av det vi skal gå igjennom i dag og muligens ikke forstått alt. Uansett skal dette være en god introduskjon til de nødvendige forutsetningene for å komme i gang med webutvikling.
 -->

---
layout: iframe-left
url: http://localhost:8080
---

### Hva vi skal lage

<br/>

# Kvist

<br/>

---
src: ./slides/workshop/react-router.md
---
<!-- Notater -->
---
src: ./slides/workshop/react-router-link.md
---
<!-- Notater -->
---