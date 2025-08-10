---
theme: seriph
title: ProHelen — Visual Instruction Builder
layout: center
class: text-center text-gray-900 dark:text-white
transition: slide-left
mdc: false
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

# ProHelen

<div class="text-xl text-gray-700 dark:text-gray-300 mt-3">A web tool to customise LLM behaviour with visual instruction building</div>

<div class="mt-6 text-base text-gray-700 dark:text-gray-300">
  <div class="font-semibold">Tunan Chen — 240000494</div>
  <div class="mt-1">Supervisor: Dr Abd Alsattar Ardati</div>
</div>

---
class: text-left text-gray-900 dark:text-white
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

# The Challenge

<div class="grid grid-cols-2 gap-10 mt-6">

<div class="bg-black/5 dark:bg-white/5 border border-black/10 dark:border-white/10 rounded-xl p-6">
  <div class="text-xs uppercase tracking-widest text-gray-500 dark:text-gray-400 mb-4">Problem</div>
  <v-clicks>
  <ul class="text-lg leading-7 space-y-3">
    <li>— Expression gulf: users know the <em>what</em> but not the <em>how</em> to tell AI</li>
    <li>— Tacit knowledge missing: persona, context, constraints, format</li>
    <li>— Iteration struggle: no strategy/feedback → random trial‑and‑error</li>
  </ul>
  </v-clicks>
</div>

<div class="bg-black/5 dark:bg-white/5 border border-black/10 dark:border-white/10 rounded-xl p-6">
  <div class="text-xs uppercase tracking-widest text-gray-500 dark:text-gray-400 mb-4">Our Approach</div>
  <v-clicks>
  <ul class="text-lg leading-7 space-y-3">
    <li>— Visual instruction blocks to externalise intent and structure</li>
    <li>— Scaffolds & templates capturing tacit knowledge</li>
    <li>— Guided iteration with live preview and evaluation hooks</li>
  </ul>
  </v-clicks>
</div>

</div>

---
class: text-left text-gray-900 dark:text-white
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

# Walkthrough (user view)

<div class="grid grid-cols-3 gap-10 mt-6">

<div class="bg-black/5 dark:bg-white/5 border border-black/10 dark:border-white/10 rounded-xl p-6 text-center">
<div class="text-sm uppercase tracking-widest text-gray-500 dark:text-gray-400">Step 1</div>
  <div class="mt-2 text-base">Drag blocks to compose Role → Task → Constraints → Format</div>
</div>

<div class="bg-black/5 dark:bg-white/5 border border-black/10 dark:border-white/10 rounded-xl p-6 text-center">
<div class="text-sm uppercase tracking-widest text-gray-500 dark:text-gray-400">Step 2</div>
  <div class="mt-2 text-base">Edit a block and see the exact instruction update live</div>
</div>

<div class="bg-black/5 dark:bg-white/5 border border-black/10 dark:border-white/10 rounded-xl p-6 text-center">
<div class="text-sm uppercase tracking-widest text-gray-500 dark:text-gray-400">Step 3</div>
  <div class="mt-2 text-base">Save as a template</div>
</div>

</div>

<div class="mt-6">
  <a href="https://www.prohelen.dev/" target="_blank" class="inline-block px-5 py-2 border border-black/20 dark:border-white/30 rounded-md text-gray-800 dark:text-gray-200 hover:bg-black/5 dark:hover:bg-white/10">
    Open Live Demo →
  </a>
  
</div>

<v-click>
<div class="mt-6 text-sm text-gray-600 dark:text-gray-400">Tip: a 45s flow — add blocks, toggle a constraint, show preview, save template</div>
</v-click>

---
class: text-left text-gray-900 dark:text-white
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

# Findings • Contribution • Next

<div class="grid grid-cols-3 gap-6 mt-4">

<div class="bg-black/5 dark:bg-white/5 border border-black/10 dark:border-white/10 rounded-xl p-5">
  <div class="text-xs uppercase tracking-widest text-gray-500 dark:text-gray-400 mb-4">Findings</div>
  <v-clicks>
  <ul class="text-base leading-6 space-y-2">
    <li>— Usability: most users completed tasks; layout and live feedback praised; needs: clearer template entry, better labels/hover tooltips, global overview for deep hierarchies</li>
    <li>— Templates strongly adopted; block architecture seen as scalable; advanced asks: richer parameter control and multi‑format export</li>
  </ul>
  </v-clicks>
</div>

<div class="bg-black/5 dark:bg-white/5 border border-black/10 dark:border-white/10 rounded-xl p-5">
  <div class="text-xs uppercase tracking-widest text-gray-500 dark:text-gray-400 mb-4">Contribution</div>
  <v-clicks>
  <ul class="text-base leading-6 space-y-2">
    <li>— Visual instruction generation with 18 semantic blocks; clear structure → behaviour mapping</li>
    <li>— Guided onboarding + context help + reusable templates + one‑click copy to democratise effective use</li>
    <li>— Modular web architecture (Next.js · React Flow · Prisma) with backend auth/data; publicly accessible prototype</li>
  </ul>
  </v-clicks>
  </div>

<div class="bg-black/5 dark:bg-white/5 border border-black/10 dark:border-white/10 rounded-xl p-5">
  <div class="text-xs uppercase tracking-widest text-gray-500 dark:text-gray-400 mb-4">What’s Next</div>
  <v-clicks>
  <ul class="text-base leading-6 space-y-2">
    <li>— AI‑assisted content per block (embedded small LMs) for refine/expand/optimise</li>
    <li>— Community platform for custom blocks/templates: versioning, dependencies, incentives</li>
    <li>— Collaboration & mobility: real‑time co‑editing, mobile canvas optimisation</li>
  </ul>
  </v-clicks>
</div>

</div>

---
layout: center
class: text-center text-gray-900 dark:text-white
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

# Thank You

<div class="text-base text-gray-600 dark:text-gray-400 mt-2">Questions?</div>

