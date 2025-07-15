---
# Theme configuration
theme: seriph
# Background
background: https://images.unsplash.com/photo-1481627834876-b7833e8f5570?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80
# Slide info
title: Don't Make Me Think - Book Review
info: |
  ## Don't Make Me Think: A Common Sense Approach to Web Usability
  Book review presentation for MSc Software Engineering students
# Layout
class: text-center
# Transitions
transition: slide-left
# Enable MDC
mdc: true
---

# Don't Make Me Think
## A Common Sense Approach to Web Usability

**By Steve Krug**

<div class="pt-8">
  <div class="text-lg opacity-80">
    Presented by: Tunan Chen
  </div>

</div>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-4 py-2 rounded cursor-pointer bg-blue-500 text-white hover:bg-blue-600">
    Let's dive in! <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
Welcome everyone! Today I'll be sharing my thoughts on "Don't Make Me Think" by Steve Krug - a book that fundamentally changed how I approach web development and user interface design.
-->

---
transition: fade-out
---

# About the Book & Author

<div class="grid grid-cols-2 gap-8 items-center">

<div>

## 👨‍💻 **Steve Krug**
- Web usability consultant since 1989
- Worked with major companies like Apple, Bloomberg, NPR
- Known for making complex UX concepts simple

<br>

## 📚 **The Book**
- **First published**: 2000 (updated in 2014)
- **Pages**: ~200 (quick read!)
- **Focus**: Practical web usability principles
- **Audience**: Anyone building websites or apps

</div>

<div class="text-center">

### 🎯 **What's it about?**

<div class="bg-blue-50 p-6 rounded-lg">
<p class="text-lg font-semibold text-blue-800">
"A practical guide to making websites that work the way users think they should"
</p>
</div>

<br>

### ✨ **Why it matters for us?**
- We build software users interact with
- Good UX = better adoption
- Principles apply to web, mobile, desktop apps

</div>

</div>

<!--
Steve Krug isn't an academic - he's a practitioner who has spent decades watching real users struggle with websites. This book distills his experience into practical advice we can use immediately in our projects.
-->

---

# Core Idea #1: Don't Make Me Think!

<div class="flex items-center justify-center h-full">

<div class="max-w-4xl">

<div class="text-center mb-8">
<h2 class="text-3xl font-bold mb-4">🧠 The Golden Rule</h2>
<p class="text-xl italic">"If something requires a large amount of thought, it's not self-evident"</p>
</div>

<div class="grid grid-cols-2 gap-8">

<div class="bg-red-50 p-6 rounded-lg">
<h3 class="text-lg font-semibold text-red-700 mb-4">❌ Bad Example</h3>
<div class="bg-white p-4 rounded border">
<div class="text-sm">
<div class="text-blue-600 cursor-pointer">Click Here</div>
<div class="text-blue-600 cursor-pointer">Products and Services</div>
<div class="text-blue-600 cursor-pointer">Solutions Hub</div>
<div class="text-blue-600 cursor-pointer">Resource Center</div>
</div>
</div>
<p class="text-sm mt-2 text-gray-600">Users think: "What's the difference between these?"</p>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<h3 class="text-lg font-semibold text-green-700 mb-4">✅ Good Example</h3>
<div class="bg-white p-4 rounded border">
<div class="text-sm">
<div class="text-blue-600 cursor-pointer">🛍️ Shop Now</div>
<div class="text-blue-600 cursor-pointer">💼 For Business</div>
<div class="text-blue-600 cursor-pointer">❓ Help & Support</div>
<div class="text-blue-600 cursor-pointer">👤 My Account</div>
</div>
</div>
<p class="text-sm mt-2 text-gray-600">Clear, obvious, no thinking required!</p>
</div>

</div>

</div>

</div>

<!--
The core principle is simple: if users have to stop and think about what something means or does, you've lost them. They're usually in a hurry and will abandon your site rather than figure it out.
-->

---

# Core Idea #2: How Users Really Behave

<div class="grid grid-cols-3 gap-6">

<div class="text-center">
<h3 class="text-2xl mb-4">👀 They Scan</h3>
<div class="bg-yellow-50 p-4 rounded-lg">
<p class="text-sm text-gray-600">Users don't read every word</p>
<p class="text-sm mt-2 text-gray-600">They look for keywords that match their goal</p>
</div>
<br>
<div class="text-xs text-gray-600">
<strong>Design implication:</strong><br>
Use clear headings, bullet points, highlighted keywords
</div>
</div>

<div class="text-center">
<h3 class="text-2xl mb-4">🎯 They Satisfice</h3>
<div class="bg-blue-50 p-4 rounded-lg">
<p class="text-sm text-gray-600">They don't find the <em>best</em> option</p>
<p class="text-sm mt-2 text-gray-600">They click the first <em>reasonable</em> option</p>
</div>
<br>
<div class="text-xs text-gray-600">
<strong>Design implication:</strong><br>
Make good options obvious and easy to find
</div>
</div>

<div class="text-center">
<h3 class="text-2xl mb-4">🤷 They Muddle Through</h3>
<div class="bg-green-50 p-4 rounded-lg">
<p class="text-sm text-gray-600">They don't read instructions</p>
<p class="text-sm mt-2 text-gray-600">They figure it out as they go</p>
</div>
<br>
<div class="text-xs text-gray-600">
<strong>Design implication:</strong><br>
Make interfaces self-explanatory
</div>
</div>

</div>

<br>

<div class="text-center bg-gray-100 p-4 rounded-lg">
<p class="text-lg font-semibold text-gray-600">💡 Key Insight</p>
<p class="text-gray-600">"Users don't mind if they can't figure out how something works, as long as they can use it successfully"</p>
</div>

<!--
This slide reveals the gap between how we think users behave versus how they actually behave. As developers, we often assume users will carefully read and consider options, but they don't.
-->

---

# Core Idea #3: Eliminate Question Marks

<div class="flex h-full items-center">

<div class="w-full">

<div class="text-center mb-6">
<h2 class="text-2xl font-bold">❓➡️✅ Remove User Confusion</h2>
<p class="text-lg">Every question mark in a user's mind is a chance for them to leave</p>
</div>

<div class="grid grid-cols-2 gap-8">

<div>
<h3 class="text-xl font-semibold mb-4">🤔 Questions Users Ask:</h3>
<ul class="space-y-2 text-sm">
<li>"Where am I?"</li>
<li>"Where should I start?"</li>
<li>"Where did they put _____?"</li>
<li>"What are the most important things on this page?"</li>
<li>"Why did they call it that?"</li>
<li>"Is that an ad or part of the site?"</li>
</ul>
</div>

<div>
<h3 class="text-xl font-semibold mb-4">✨ Design Solutions:</h3>
<ul class="space-y-2 text-sm">
<li><strong>Clear page titles</strong> and breadcrumbs</li>
<li><strong>Obvious starting points</strong> and CTAs</li>
<li><strong>Logical navigation</strong> structure</li>
<li><strong>Visual hierarchy</strong> with sizing/color</li>
<li><strong>Conventional naming</strong> (no creativity!)</li>
<li><strong>Clear visual separation</strong> from ads</li>
</ul>
</div>

  </div>

<div class="mt-6 text-center mb-12">
<div class="bg-yellow-100 p-4 rounded-lg inline-block">
<p class="text-sm font-semibold text-gray-600">🎯 Goal: Users should never think "Huh?" when using your app</p>
  </div>
</div>

</div>

</div>

<!--
Every moment a user spends confused is a moment they might decide your app isn't worth the trouble. Our job is to eliminate these moments of confusion through clear, conventional design.
-->

---

# Core Idea #4: Testing Beats Arguments

<div class="h-full flex items-center">

<div class="w-full">

<div class="text-center mb-6">
<h2 class="text-2xl font-bold">🧪 "Testing one user is 100% better than testing none"</h2>
</div>

<div class="grid grid-cols-2 gap-8">

<div class="bg-red-50 p-6 rounded-lg">
<h3 class="text-lg font-semibold text-red-700 mb-4">😤 What Usually Happens</h3>
<ul class="text-sm space-y-2">
<li class="text-gray-600">Designer: "Users will understand this dropdown"</li>
<li class="text-gray-600">Developer: "It's obvious what this button does"</li>
<li class="text-gray-600">Manager: "We need more features on the homepage"</li>
<li class="text-gray-600">Everyone argues based on opinions</li>
<li class="text-gray-600">Loudest voice wins</li>
</ul>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<h3 class="text-lg font-semibold text-green-700 mb-4">✅ What Should Happen</h3>
<ul class="text-sm space-y-2">
<li class="text-gray-600">Find 3-5 users (even friends/classmates)</li>
<li class="text-gray-600">Give them a simple task</li>
<li class="text-gray-600">Watch them use your app</li>
<li class="text-gray-600">Note where they get confused</li>
<li class="text-gray-600">Fix the obvious problems</li>
</ul>
</div>

</div>

<div class="mt-6 mb-12">
<div class="bg-blue-100 p-4 rounded-lg text-center">
<h4 class="font-semibold mb-2 text-gray-600">💡 Krug's Simple Testing Method</h4>
<p class="text-sm text-gray-600">"Morning usability tests every month, 3 users, focus on big problems, make small improvements"</p>
</div>
</div>

</div>

</div>

<!--
This might be the most valuable lesson for us as software engineers. We often debate design decisions in meetings, but 5 minutes watching a real user struggle with our interface teaches us more than hours of discussion.
-->

---
transition: slide-up
---

# My Takeaways & Application

<div class="grid grid-cols-2 gap-8 h-full">

<div class="flex flex-col justify-start pt-8">

## 🚀 **How I Applied This**

### In My AI Prompt Builder:
<ul class="text-sm space-y-1 text-gray-600">
<li><strong>Before</strong>: Complex prompt engineering interface with technical jargon</li>
<li><strong>After</strong>: Visual building blocks with intuitive categories</li>
<li><strong>Result</strong>: User success rate up directly</li>
</ul>

<br>

### Specific Changes:
<ul class="text-sm space-y-1 text-gray-600">
<li>✅ Replaced technical terms with visual blocks</li>
<li>✅ Added clear category system (Role, Style, Task, etc.)</li>
<li>✅ Made "Start Creating" the primary action</li>
<li>✅ Used intuitive icons and visual cues</li>
</ul>

</div>

<div class="flex flex-col justify-start pt-8">

## 💭 **Personal Insights**

<div class="space-y-4 mb-6">

<div class="bg-yellow-50 px-4 py-2 rounded-lg">
<p class="font-semibold text-yellow-800">💡 "Visual over Technical"</p>
<p class="text-sm text-gray-600">Users prefer intuitive blocks over complex prompts</p>
</div>

<div class="bg-blue-50 px-4 py-2 rounded-lg">
<p class="font-semibold text-blue-800">⚡ "A/B Test Everything"</p>
<p class="text-sm text-gray-600">Multiple iterations led to optimal UX</p>
</div>

<div class="bg-green-50 px-4 py-2 rounded-lg">
<p class="font-semibold text-green-800">🎯 "Direct Access"</p>
<p class="text-sm text-gray-600">Users find what they need immediately</p>
</div>

</div>



</div>

</div>

<!--
By applying "Don't Make Me Think" principles to our AI Prompt Builder, we transformed a complex technical process into an intuitive visual experience. Multiple A/B tests helped us optimize the interface for maximum user success.
-->

---

# Why You Should Read This Book

<div class="flex h-full items-center">

<div class="w-full space-y-6">

<div class="grid grid-cols-3 gap-6">

<div class="bg-purple-50 p-4 rounded-lg">
<h3 class="text-lg font-semibold text-purple-700 mb-2">⚡ Quick Read</h3>
<p class="text-sm text-gray-600">~3 hours, very practical</p>
</div>

<div class="bg-blue-50 p-4 rounded-lg">
<h3 class="text-lg font-semibold text-blue-700 mb-2">🎯 Immediately Useful</h3>
<p class="text-sm text-gray-600">Apply lessons to any project</p>
</div>

<div class="bg-green-50 p-4 rounded-lg">
<h3 class="text-lg font-semibold text-green-700 mb-2">💼 Career Relevant</h3>
<p class="text-sm text-gray-600">UX skills valuable everywhere</p>
</div>

</div>

<div class="text-center">
<p class="text-lg mb-2 text-gray-700">👨‍💻 <strong>For Software Engineers:</strong></p>
<p class="text-gray-600">This book bridges the gap between <span class="text-blue-600 font-semibold">technical implementation</span> and <span class="text-green-600 font-semibold">user experience</span></p>
</div>

<div class="bg-gray-100 p-4 rounded-lg text-center">
<p class="text-lg font-semibold text-gray-700">"Every software engineer should understand how users actually interact with their code"</p>
<p class="text-sm text-gray-600 mt-2">- This book gives you that understanding</p>
</div>



</div>

</div>




<!--
This book is particularly valuable for software engineers because it helps us think beyond just making code work - it helps us make code that works well for real users.
-->

---
layout: center
class: text-center
---

# Thank You!

<div class="space-y-6">

<div class="text-xl">
Questions or Discussion?
</div>

<div class="grid grid-cols-2 gap-8 max-w-2xl mx-auto text-left">

<div>
<h3 class="font-semibold mb-2">💭 Think About:</h3>
<ul class="text-sm space-y-1">
<li>Your current projects - where do users get confused?</li>
<li>Have you ever tested with real users?</li>
<li>What "creative" UI choices might be hurting usability?</li>
</ul>
</div>

<div>
<h3 class="font-semibold mb-2">📚 Next Steps:</h3>
<ul class="text-sm space-y-1">
<li>Read "Don't Make Me Think" (available in library)</li>

</ul>
</div>

</div>



</div>
<!--
I hope this overview has convinced you to pick up this book. It's one of those rare technical books that's both easy to read and immediately practical. Thank you for your attention!
-->

