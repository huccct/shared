---
theme: hep
title: ProHelen — Visual Instruction Builder
layout: center
class: text-center
transition: slide-left
mdc: true
clicks: 0
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

<!-- Decorative background elements -->
<div class="absolute inset-0 overflow-hidden pointer-events-none">
  <div class="absolute top-20 left-20 w-32 h-32 bg-gradient-to-br from-gray-800/40 to-slate-800/40 dark:from-gray-700/30 dark:to-slate-700/30 rounded-full blur-xl opacity-80"></div>
  <div class="absolute bottom-32 right-16 w-48 h-48 bg-gradient-to-tl from-zinc-800/30 to-neutral-800/30 dark:from-zinc-700/20 dark:to-neutral-700/20 rounded-full blur-2xl opacity-60"></div>
  <div class="absolute top-1/2 left-1/4 w-2 h-16 bg-gradient-to-b from-gray-600 to-slate-700 opacity-40 transform rotate-12"></div>
  <div class="absolute top-1/3 right-1/3 w-1 h-12 bg-gradient-to-b from-zinc-600 to-neutral-700 opacity-50 transform -rotate-45"></div>
</div>

<div class="relative z-10">

# **ProHelen**
<div class="text-3xl font-light text-gray-700 dark:text-gray-300 mb-8">Visual Instruction Builder</div>

<div class="mt-12 space-y-4">
  <div class="text-xl font-medium">Tunan Chen — 240000394</div>
  <div class="text-lg opacity-70">Supervisor: Dr Abd Alsattar Ardati</div>
</div>

<!-- Subtle accent line -->
<div class="mt-12 mx-auto w-24 h-px bg-gradient-to-r from-transparent via-gray-600 dark:via-gray-400 to-transparent opacity-60"></div>

</div>

<!--
Good morning/afternoon everyone,

My name is Tunan Chen, and today I'm excited to present ProHelen - a Visual Instruction Builder that transforms how people communicate with AI.

For this project, the core question we're addressing is: How can we bridge the gap between what people want to tell AI and what they actually manage to communicate?

Let's dive into this problem.
-->

---
layout: default
class: text-left
clicks: 6
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

# Problem • Background • Method

<div class="grid grid-cols-2 gap-8 items-start mt-4">

<div>

<div v-click="1" v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }">

### The Problem We're Solving

<!-- Simple Expression Gap Visual -->
<div class="mb-6 p-4 bg-blue-50 dark:bg-blue-900/20 rounded-lg border border-blue-200 dark:border-blue-800">
  <div class="flex items-center justify-center space-x-4">
    <!-- User thinking -->
    <div class="text-center">
      <div class="w-16 h-16 bg-white dark:bg-gray-800 rounded-full border-2 border-blue-300 dark:border-blue-600 flex items-center justify-center">
        <span class="text-2xl">🧠</span>
      </div>
      <p class="mt-2 text-xs font-medium text-gray-800 dark:text-gray-200">What I want</p>
    </div>
    <!-- Arrow with question mark -->
    <div class="text-center">
      <div class="text-2xl text-red-500 dark:text-red-400">❌</div>
      <p class="mt-2 text-xs text-red-600 dark:text-red-400">Communication gap</p>
    </div>
    <!-- AI confused -->
    <div class="text-center">
      <div class="w-16 h-16 bg-white dark:bg-gray-800 rounded-full border-2 border-gray-300 dark:border-gray-600 flex items-center justify-center">
        <span class="text-2xl">🤖</span>
      </div>
      <p class="mt-2 text-xs font-medium text-gray-800 dark:text-gray-200">What AI gives</p>
    </div>
  </div>
</div>

**Most people struggle to tell AI exactly what they want**

<div class="mt-4 p-3 bg-gray-50 dark:bg-gray-800 rounded text-sm">
  <div class="text-red-600 dark:text-red-400 font-medium">❌ Typical attempt:</div>
  <div class="italic">"Write me a good email"</div>
  <div class="text-green-600 dark:text-green-400 font-medium mt-2">✅ With ProHelen:</div>
  <div class="text-xs">Role: Professional | Task: Email | Tone: Formal | Length: Brief</div>
</div>

</div>

<div v-click="2">
<ul class="text-base space-y-3 mt-4">
  <li><strong>You know what you want</strong> but don't know how to ask for it</li>
  <li><strong>Missing the "how"</strong>: What tone? What format? What constraints?</li>
  <li><strong>Endless trial and error</strong>: Keep typing until something works</li>
</ul>
</div>

</div>

<div>

<div v-click="3" v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }">

### Our Solution: Make It Visual

<div class="mb-6 p-4 bg-green-50 dark:bg-green-900/20 rounded-lg border border-green-200 dark:border-green-800">
  <div class="flex items-center justify-center space-x-2">
    <!-- Building blocks -->
    <div class="w-12 h-8 bg-blue-400 dark:bg-blue-500 rounded text-white text-xs flex items-center justify-center">Role</div>
    <span class="text-lg text-gray-800 dark:text-gray-200">+</span>
    <div class="w-12 h-8 bg-green-400 dark:bg-green-500 rounded text-white text-xs flex items-center justify-center">Task</div>
    <span class="text-lg text-gray-800 dark:text-gray-200">+</span>
    <div class="w-12 h-8 bg-orange-400 dark:bg-orange-500 rounded text-white text-xs flex items-center justify-center">Rules</div>
    <span class="text-lg text-gray-800 dark:text-gray-200">=</span>
    <div class="w-12 h-8 bg-purple-400 dark:bg-purple-500 rounded text-white text-xs flex items-center justify-center">Perfect</div>
  </div>
  <p class="text-center mt-2 text-sm font-medium text-gray-800 dark:text-gray-200">Like building with LEGO blocks!</p>
</div>

</div>

<div v-click="4">
<ul class="text-base space-y-3">
  <li><strong>Drag and drop blocks</strong> instead of writing from scratch</li>
  <li><strong>See your instruction</strong> build up as you add blocks</li>
  <li><strong>Save as templates</strong> to reuse later</li>
</ul>
</div>

<div v-click="5" v-motion
  :initial="{ opacity: 0, y: 20 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 500 } }">

### Why ProHelen Is Different

</div>

<div v-click="6" v-motion
  :initial="{ opacity: 0, y: 20 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600, delay: 200 } }">
<div class="mt-4">

| What others do | What we do |
|----------------|------------|
| ❌ Text box only | ✅ Visual building blocks |
| ❌ No live preview | ✅ See changes instantly |
| ❌ Start from scratch each time | ✅ Reusable templates |
| ❌ Figure it out yourself | ✅ Step-by-step guidance |

</div>
</div>

</div>

</div>

<!--
开场 (Click 1 出现时)
Let me start with the fundamental problem we're solving. Most people struggle to tell AI exactly what they want. Look at this communication gap here - you have a clear idea in your head, but there’s a big gap between what you want and what the AI gives you.

问题分析 (Click 2 出现时)
Why does this happen? Well, there are three main reasons. First, you know what you want but not how to ask for it. Second, you're missing all the specifics - what tone should it use? What format? What constraints? And third, it just becomes this endless cycle of trial and error until something works.

解决方案介绍 (Click 3 出现时)
So our solution was to make this entire process visual. Think of it like building with LEGO blocks - instead of trying to describe everything in words, you just drag and drop to get the perfect prompt.

优势说明 (Click 4 出现时)
This gives you three key advantages: you can drag and drop blocks instead of writing from empty, you see your instruction building up in real-time, and you can save successful combinations as templates for later use.

差异化对比 (Click 5-6 出现时)
But what makes ProHelen different from existing tools? Well, here's the key distinction - while others just give you a text box and say "figure it out yourself," we provide visual building blocks, instant previews, reusable templates, and step-by-step guidance. In short, ProHelen makes prompt creation easier, faster.
-->

---
layout: default
class: text-left
clicks: 2
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

## Tool Walkthrough

<div class="space-y-8 mt-6">

<div v-click="1" v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }"
  class="text-center">

### Single User Journey: Emma's Business Consultant Template Creation

**Challenge:** Inconsistent AI analysis → **Solution:** 45-second visual workflow → **Result:** Team consistency



</div>

<div v-click="2" v-motion
  :initial="{ opacity: 0, scale: 0.95 }"
  :enter="{ opacity: 1, scale: 1, transition: { duration: 800, delay: 200 } }"
  class="w-full">

<div class="w-full max-w-2xl mx-auto">
  <video 
    src="./CleanShot 2025-08-15 at 11.03.26.mp4" 
    class="w-full rounded-lg shadow-lg border-2 border-gray-300 dark:border-gray-600"
    controls
    autoplay
    muted
    loop
    preload="metadata">
    <source src="./CleanShot 2025-08-15 at 11.03.26.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div class="mt-6 grid grid-cols-1 md:grid-cols-3 gap-4 text-center">
  <div v-motion
    :initial="{ opacity: 0, y: 20 }"
    :enter="{ opacity: 1, y: 0, transition: { duration: 400, delay: 500 } }"
    class="p-3 bg-green-50 dark:bg-green-900/20 rounded">
    <div class="italic text-sm">"I can see exactly what I'm building"</div>
    <div class="text-xs mt-1 font-medium">→ Live preview priority</div>
  </div>
  <div v-motion
    :initial="{ opacity: 0, y: 20 }"
    :enter="{ opacity: 1, y: 0, transition: { duration: 400, delay: 600 } }"
    class="p-3 bg-blue-50 dark:bg-blue-900/20 rounded">
    <div class="italic text-sm">"Templates give me frameworks"</div>
    <div class="text-xs mt-1 font-medium">→ Expert guidance</div>
  </div>
  <div v-motion
    :initial="{ opacity: 0, y: 20 }"
    :enter="{ opacity: 1, y: 0, transition: { duration: 400, delay: 700 } }"
    class="p-3 bg-purple-50 dark:bg-purple-900/20 rounded">
    <div class="italic text-sm">"Much faster than writing prompts"</div>
    <div class="text-xs mt-1 font-medium">→ Visual approach wins</div>
  </div>
</div>

</div>

</div>

<!--
Click 1 出现时
Let me show you how this works. Meet Emma, a business consultant who is upset about AI giving different results. We made her a 45-second visual workflow that changed her team’s work, giving consistent and professional results every time.


Click 2 出现时 (GIF播放)
Now let’s take a look at Emma’s workflow. She first drags in “Role Definition” and selects “Business Consultant” from the presets. Then she adds “Goal Setting” – this isn’t just a regular text box, but a complete professional framework. After that she sets the output format and views a live preview on the right. Finally, she saves it as a template that her entire team can use.

This workflow gave us valuable user feedback. [指向三个反馈卡片] These insights shaped our design. Users said:
- "I can see exactly what I'm building" – confirming live preview is key.
- "Templates give me frameworks I wouldn't think of" – showing expert guidance matters.
- "Much faster than writing prompts" – proving the visual approach works.
-->

---
layout: default
class: text-left
clicks: 5
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

## Findings • Contribution • Next

<div v-click="1" v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }"
  class="text-xl mt-6">

### Findings

<div v-click="2">
<ul class="space-y-2">
  <li><strong>High task completion</strong> with positive feedback on layout and live preview</li>
  <li><strong>Template adoption</strong> validates block architecture scalability</li>
  <li><strong>Clear requests</strong>: better labels, global overview, richer controls</li>
</ul>
</div>

</div>

<div v-click="3" v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }"
  class="text-xl mt-6">

### Contribution  

<div v-click="4">
<ul class="space-y-2">
  <li><strong>Visual instruction system</strong> with 18 semantic blocks mapping structure to behavior</li>
  <li><strong>Democratized access</strong> via guided onboarding, templates, one-click export</li>
  <li><strong>Working prototype</strong> with full-stack architecture deployed at <a href="https://prohelen.dev" target="_blank" class="text-blue-500 hover:text-blue-600">prohelen.dev</a></li>
</ul>
</div>

</div>

<div v-click="5" v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }"
  class="text-xl mt-6">

### What's Next

<div>
<ul class="space-y-2">
  <li><strong>AI-assisted refinement</strong> with embedded models per block</li>
  <li><strong>Community platform</strong> for custom blocks, templates, sharing</li>
  <li><strong>Real-time collaboration</strong> and mobile optimization</li>
</ul>
</div>

</div>

<!--
Click 1-2: Findings
So what did we discover? Three key findings: high task completion with positive feedback on layout and live preview. Strong template adoption validated our block architecture scalability. And users gave specific, actionable requests - better labels, global overview, richer controls. These weren't complaints, they were our roadmap.

Click 3-4: Contribution 
Our main contributions: We created a visual instruction system with 18 building blocks that directly map structure to AI behavior. We democratized prompt engineering through guided templates and one-click export - making professional instruction building accessible to everyone. And we delivered a working prototype deployed at prohelen.dev.

Click 5: What's Next 
Looking ahead: I hope to embed AI models within each block for intelligent optimization, build a community platform for users to co-create high-quality prompts, and support real-time collaboration. This opens up entirely new possibilities for human-AI interaction—and this is just the beginning.
-->

---
layout: center
class: text-center text-gray-900 dark:text-white
---

<div class="absolute inset-0 overflow-hidden pointer-events-none">
  <div class="absolute top-20 left-20 w-32 h-32 bg-gradient-to-br from-gray-800/40 to-slate-800/40 dark:from-gray-700/30 dark:to-slate-700/30 rounded-full blur-xl opacity-80"></div>
  <div class="absolute bottom-32 right-16 w-48 h-48 bg-gradient-to-tl from-zinc-800/30 to-neutral-800/30 dark:from-zinc-700/20 dark:to-neutral-700/20 rounded-full blur-2xl opacity-60"></div>
  <div class="absolute top-1/2 left-1/4 w-2 h-16 bg-gradient-to-b from-gray-600 to-slate-700 opacity-40 transform rotate-12"></div>
  <div class="absolute top-1/3 right-1/3 w-1 h-12 bg-gradient-to-b from-zinc-600 to-neutral-700 opacity-50 transform -rotate-45"></div>
</div>

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

# Thank You

<div class="text-xl text-gray-600 dark:text-gray-400 mt-6">Questions?</div>

<!-- Subtle accent line -->
<div class="mt-12 mx-auto w-24 h-px bg-gradient-to-r from-transparent via-gray-600 dark:via-gray-400 to-transparent opacity-60"></div>

<!--
Thank you for your attention.

ProHelen demonstrates that visual interfaces can fundamentally improve how people communicate with AI systems.

I'm happy to answer any questions you might have.
-->
