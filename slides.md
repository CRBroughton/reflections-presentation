---
theme: default
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: Reflections
preload: false
---

# Reflections

Glances on our recent past

<div class="mt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<style lang="scss">
h1, p {
  @apply pl-2
}
</style>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
preload: false
---
# What Are Reflections?

  <div
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    <h6>🕒 Reflections are bit-sized periodic glances at our recent past</h6>
  </div>

 

  <div
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 6000, duration: 1000 } }">
    <ul>
      <li><twemoji-rocket /> <span class="font-bold">Objective driven</span> - Did you accomplish your goals? </li>
      <li><twemoji-thinking-face  /> <span class="font-bold">Reflective</span> - Look back at your last month</li>
      <li><twemoji-thumbs-down  />  <span class="font-bold">Critical</span> - Find your mistakes</li>
      <li><twemoji-clapping-hands  />  <span class="font-bold">Satisfaction</span> - How was that month for you?</li>
      <li><twemoji-technologist /> <span class="font-bold">Reformative</span> - Aim for a better day, month, year</li>
      <li><twemoji-slightly-smiling-face  /> <span class="font-bold">Personal</span> - Time spent on ourselves</li>
  </ul> 
</div>


  <div
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 14000, duration: 1000 } }">
    <h6>🗓️ Plans for tomorrow</h6>
  </div>

  <div
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 18000, duration: 1000 } }">
    <ul>
      <li>⚽ <span class="font-bold">Goals</span> - Drive your progress through achievable goals </li>
      <li>⏰ <span class="font-bold">Reminders</span> - Improve your steady progress through reminders</li>
  </ul> 
</div>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h6 {
  @apply my-5
}
</style>

---
preload: false
---

# August Reflections 

<div class="flex justify-center w-1/2 h-full pb-8">
  <div class="flex gap-2">
    <img
    src="/screenshot1.png"
  />
  <img
    src="/screenshot2.png"
  />
  </div>
</div>


---
preload: false
---

# Why I Reflect
<div
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 3000, duration: 1000 } }">
    <ul>
      <li><twemoji-rocket /> Continuous Improvement</li>
      <li><twemoji-thinking-face  /> Find my weakness and "Patch" them. Exploit my strengths to the fullest</li>
      <li><twemoji-technologist /> Study the past, plan for tomorrow</li>
    </ul>
</div>

<style>
h6 {
  @apply my-5
}
</style>
---
layout: center
class: text-center
---

# End

Feel free to ask questions :)
