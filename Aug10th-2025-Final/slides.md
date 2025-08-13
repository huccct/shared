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

This project was supervised by Dr Abd Alsattar Ardati, and represents my final year dissertation work.

The core question we're addressing is: How can we bridge the gap between what people want to tell AI and what they actually manage to communicate?

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
Click 1: Problem Introduction
Let me start with the fundamental problem we're solving.

Most people struggle to tell AI exactly what they want. Look at this communication gap - 
[指向可视化图表]
You have a clear idea in your head, but there's this massive disconnect between your intention and what the AI actually delivers.

Click 2: Problem Details
Why does this happen? Three main reasons:

First, you know what you want but don't know how to ask for it. You might want a professional email, but what does "professional" actually mean to an AI?

Second, you're missing the "how" - What tone should it use? What format? What constraints should it follow?

Third, it becomes endless trial and error. You keep typing different versions until something finally works - if you're lucky.

Click 3: Solution Introduction
So our solution was to make this process visual.
[指向LEGO积木可视化]
Think of it like building with LEGO blocks. Instead of trying to describe everything in words, you simply drag and drop: Role plus Task plus Rules equals Perfect instruction.

Click 4: Solution Benefits
This approach gives you three key advantages:

You drag and drop blocks instead of writing from scratch - much faster and less error-prone.

You see your instruction build up in real-time as you add blocks - immediate feedback.

And you can save successful combinations as templates to reuse later - no more starting over.

Click 5: Differentiation Header
But what makes ProHelen different from existing tools?

Click 6: Comparison Table
Here's the key distinction:
[指向表格]
While others give you just a text box and say "figure it out yourself," we provide visual building blocks, instant previews, reusable templates, and step-by-step guidance.

This isn't just another prompt tool - it's a complete visual instruction system.
-->

---
layout: default
class: text-left
clicks: 3
---

<img src="./logo.png" class="fixed top-4 right-4 h-10 opacity-80" />

## Tool Demo

<div v-click="1" v-motion
  :initial="{ opacity: 0, scale: 0.9 }"
  :enter="{ opacity: 1, scale: 1, transition: { duration: 600 } }"
  class="mt-2 text-center">
  <a href="https://www.prohelen.dev/" target="_blank" class="text-lg underline underline-offset-4 hover:opacity-80">
    → Live Demo
  </a>
</div>

## Meet Justin's Journey

<div class="grid grid-cols-2 gap-12 mt-6">
  <div class="space-y-6">
    <div v-click="2" v-motion
      :initial="{ opacity: 0, x: -50 }"
      :enter="{ opacity: 1, x: 0, transition: { duration: 500, delay: 100 } }">
      <div class="space-y-4">
        <div>
          <div class="opacity-70 text-sm">Justin, marketing manager:</div>
          <div class="italic">"I waste hours crafting AI prompts that give inconsistent results"</div>
        </div>
        <div>
          <div class="opacity-70 text-sm">Opens ProHelen, 45 seconds later:</div>
          <div>Drags Role + Task → sees live preview → "This finally makes sense!"</div>
        </div>
        <div>
          <div class="opacity-70 text-sm">Saves template:</div>
          <div class="italic">"Now my whole team can create consistent instructions"</div>
        </div>
      </div>
    </div>
    <div v-motion
      :initial="{ opacity: 0, x: -50 }"
      :enter="{ opacity: 1, x: 0, transition: { duration: 500, delay: 600 } }"
      class="italic text-sm opacity-80 border-l-2 border-gray-300 pl-3">
      "I realized users needed immediate visual feedback, not more complexity"
    </div>
  </div>

  <div class="space-y-6">
    <div v-click="3" v-motion
      :initial="{ opacity: 0, x: 50 }"
      :enter="{ opacity: 1, x: 0, transition: { duration: 500 } }">
      <div class="space-y-4">
        <div class="text-lg font-medium">Before → After</div>
        <div class="p-3 rounded border-l-4 border-red-400 bg-red-50 dark:bg-red-900/20">
          <div class="text-xs opacity-70 mb-1">Before: Messy prompt</div>
          <div class="text-sm">"Write me marketing copy that's professional but not too formal and make it engaging..."</div>
        </div>
        <div class="text-center text-2xl">↓</div>
        <div class="p-3 rounded border-l-4 border-green-400 bg-green-50 dark:bg-green-900/20">
          <div class="text-xs opacity-70 mb-1">After: Structured instruction</div>
          <div class="text-sm">Role: Marketing copywriter<br/>Task: Create engaging product copy<br/>Format: 150 words, conversational tone</div>
        </div>
        <div class="text-xs italic opacity-80">
          User feedback: "Templates save me 2 hours per week"
        </div>
      </div>
    </div>
  </div>
</div>

<!--
Click 1: Demo Link
Before I explain the technical details, let me show you how this actually works in practice.
[指向链接]
This is our live demo at prohelen.dev - fully functional and deployed.

But let me tell you a story that illustrates the real impact.

Click 2: Justin's Story
Meet Justin - he's a marketing manager who was wasting hours crafting AI prompts with inconsistent results. Sound familiar?

Here's what happened when he tried ProHelen:

He opens the tool, and within just 45 seconds, he drags a Role block, adds a Task block, sees the live preview updating, and says "This finally makes sense!"

Then he saves it as a template and tells his team: "Now my whole team can create consistent instructions."

This story taught me something crucial: I realized that users needed immediate visual feedback, not more complexity.

Click 3: Before/After Comparison
Let me show you the transformation:
[指向Before部分]
Before: His prompt was a mess - "Write me marketing copy that's professional but not too formal and make it engaging..." - vague and confusing.

[指向After部分]
After: Clean, structured instruction - "Role: Marketing copywriter, Task: Create engaging product copy, Format: 150 words, conversational tone."

The result? User feedback: "Templates save me 2 hours per week."

This isn't just about better prompts - it's about transforming how people think about AI communication.
-->

---
layout: default
class: text-left
clicks: 9
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
  <li v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 100 } }">
    <strong>High task completion</strong> with positive feedback on layout and live preview
  </li>
  <li v-click="3" v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 200 } }">
    <strong>Template adoption</strong> validates block architecture scalability
  </li>
  <li v-click="4" v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 300 } }">
    <strong>Requests</strong>: clearer labels, global overview, richer parameter control
  </li>
</ul>
</div>

</div>

<div v-click="5" v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }"
  class="text-xl mt-6">

### Contribution  

<div v-click="6">
<ul class="space-y-2">
  <li v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 100 } }">
    <strong>Visual instruction system</strong> with 18 semantic blocks mapping structure to behavior
  </li>
  <li v-click="7" v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 200 } }">
    <strong>Democratized access</strong> via guided onboarding, templates, one-click export
  </li>
  <li v-click="8" v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 300 } }">
    <strong>Working prototype</strong> with full-stack architecture deployed at prohelen.dev
  </li>
</ul>
</div>

</div>

<div v-click="9" v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }"
  class="text-xl mt-6">

### What's Next

<div>
<ul class="space-y-2">
  <li v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 100 } }">
    <strong>AI-assisted refinement</strong> with embedded models per block
  </li>
  <li v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 200 } }">
    <strong>Community platform</strong> for custom blocks, templates, sharing
  </li>
  <li v-motion
    :initial="{ opacity: 0, x: -30 }"
    :enter="{ opacity: 1, x: 0, transition: { duration: 400, delay: 300 } }">
    <strong>Real-time collaboration</strong> and mobile optimization
  </li>
</ul>
</div>

</div>

<!--
Click 1-2: Findings Introduction
So what did we discover through user testing and deployment?

Click 3-4: Specific Findings
Three key findings emerged:

First, we achieved high task completion rates with consistently positive feedback on the layout and live preview functionality.

Second, strong template adoption validated that our block architecture is scalable and genuinely useful.

Third, user requests focused on clearer labels, better global overview, and richer parameter control - all actionable improvements.

Click 5-6: Contribution Header & Details
Based on these findings, here are our main contributions to the field:

Click 7-8: Specific Contributions
We created a visual instruction system with 18 semantic blocks that directly map interface structure to AI behavior.

We democratized access to effective prompt engineering through guided onboarding, ready-made templates, and one-click export functionality.

And we delivered a working prototype with full-stack architecture, deployed and accessible at prohelen.dev.

Click 9: Future Work
Looking ahead, we see three exciting directions:

AI-assisted refinement with embedded models that can suggest improvements for each block type.

A community platform where users can create custom blocks, share templates, and collaborate.

And real-time collaboration features with mobile optimization for on-the-go instruction building.

This work opens up entirely new possibilities for human-AI interaction design.
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
