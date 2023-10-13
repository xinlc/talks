---
theme: dracula
layout: cover
class: text-center
background: https://source.unsplash.com/collection/94734566/1920x1080
favicon: https://upload.wikimedia.org/wikipedia/commons/9/9f/Vimlogo.svg
titleTemplate: '%s'
highlighter: shiki
lineNumbers: false
selectable: true
css: unocss
colorSchema: dark
transition: fade-out
mdc: true
hideInToc: true
growX: 50
growY: 130
growSize: 1.5
---

# 编辑器之神 - Vim

分享人： Richard

2023-10-13

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/xinlc" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
src: ../../reuse/intro.zh.md
hideInToc: true
growX: 10
growY: 90
style: 'padding-left: 8rem;'
---

---
src: ./pages/02-目录.md
hideInToc: true
---

---
src: ./pages/03-概述.md
---

---
src: ./pages/04-入门.md
---

---
src: ./pages/05-进阶.md
---

---
src: ./pages/06-扩展.md
---

---
src: ./pages/99-总结.md
---

---
src: ../../reuse/thanks.zh.md
hideInToc: true
growX: 50
growY: 120
---
