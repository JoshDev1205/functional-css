---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://iili.io/hYtdjR.png
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false

fonts:
  sans: 'Open sans'
---

# Programacion Funcional en CSS

By @JoshDev1205

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/JoshDev1205/" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>
---
layout: default
---

# ¿Qué es Programacion Funcional?

<p class="pt-4"> La programación funcional es un paradigma declarativo. Nos enfocaremos en <strong>"qué"</strong> estamos haciendo y no en <strong>"cómo"</strong> se está haciendo que sería el enfoque imperativo. Esto quiere decir que nosotros expresaremos nuestra lógica sin describir controles de flujo; no usaremos ciclos o condicionales.</p>

```js
const arr = [2, 4, 6]
const arraySum = arr.reduce()
console.log(`El sumatorio resulta en ${arraySum}`)
// El sumatorio resulta en 12 
```

<style>
p {
  font-size: 24px;
}
</style>

---

# Principios Base

- 📝 **One Input/One Output** - Una entrada un solo retorno
- 🎨 **No side effects** - Sin efectos colaterales
- 🧑‍💻 **Composable** - Abstraccion de funcionalidad

---

# Frustraciones en CSS

- 📝 **Complex to reason about**
- 🎨 **Extrem class specificity**
- 🧑‍💻 **Mutability and Side effects**

---

# ¿Cómo podriamos ser funcionales en CSS?

- 📝 **One Element/ One Style**
- 🎨 **No Cascade**
- 🧑‍💻 **Composables Classes**

```html
<div class="flex justify-center items-center">
  <p class="font-bold italic text-red-400">Im a developer 😎</p>
</div>

```

---

# A donde nos lleva esto ?

<p class="pt-4"> Parte de todo este concepto nos lleva a:</p>

- 📝 **Utility First**
- 🎨 **CSS in JS**

<style>
p {
  font-size: 24px;
}
</style>

---

# Tools para tener Functional CSS

## Utility First
- 📝 **TailwindCSS**
- 🎨 **WindiCSS**
- 🧑‍💻 **UnoCSS**

## CSS in JS
- 📝 **Vanilla Extract**
- 🎨 **Styled Components**
- 🧑‍💻 **Emotion**
---
---

# ¿Qué viene hacia adelante?

<p class="text-center pt-32">JIT</p>

<style>
  p {
    font-size: 64px;
  }
</style>
---