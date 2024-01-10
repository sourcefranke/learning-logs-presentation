---
theme: seriph
background: https://wallpapercave.com/wp/wp8149811.jpg
class: text-center
highlighter: shiki
lineNumbers: false
transition: fade
title: A Learning Log Process
mdc: true
---

# A Learning Log Process

How to handle so many interesting topics coming in

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2 items-baseline opacity-50">
    <span class="text-sm">v2023-11-15</span>
    <a href="https://github.com/sourcefranke/learning-logs-presentation" target="_blank" alt="GitHub"
        class="text-xl slidev-icon-btn !border-none !hover:text-white">
        <carbon-logo-github />
    </a>
</div>


---

# Issue

So many sources of information & ideas to follow up with ...

<div style="display: flex; justify-content: center; align-items: center;">
```mermaid {scale: 1.1}
flowchart TD
    work --> me((poor me\n;P))
    conferences --> me
    training --> me
    meetups --> me
    bc[bar camps] --> me
    internet --> me
    etc[... etc.] --> me
    me --> trash(many things\ngot lost\non the way)
```
</div>


---

# Process

Plan of action for facing the wild horde of impressions to chase after & to follow up with ;-P

```mermaid {scale: 1.3}
flowchart LR
    new[new items] -- collect --> b[(backlog)]
    -- prioritize\nregularly --> b -- pick item\nwith highest\npriority -->
    w([doing]) -- finalize --> out[some visible\noutcome] -- repeat\nprocess --> b
```


---

# Backlog

It all started with an Excel sheet ...

| **Topic**       | **Source**     | **Input Date** | **Priority** | **Connection**         | **Outcome**               | **Status** | **Comments**                            |
|-----------------|----------------|----------------|--------------|------------------------|---------------------------|------------|-----------------------------------------|
| Learning Logs   | personal need  | 2023/8/15      | 1            | Personal Need          | DigiCamp Session          | Started    | Develop some process you can talk about |
| Slidev          | Community Talk | 2022/9/23      | 1            | Tool for presentations | Talk about some topic     | Finished   | Prepare and publish slides for session  |
| Spock Framework | Meetup         | 2021/8/12      | 4            | Work project           | Direct use for daily work | Entered    | Write Unit tests more efficiently       |


---

# Personal Connection

<div style="display: flex; justify-content: center;">
    <img src="/connection.png" style="width:420px; height:420px;" />
</div>


---

# Outcome

So many possibilities to transfer your learning achievements into some <u>___visible___</u> outcome!

<div style="text-align: center">
```mermaid {scale: 1}
mindmap
  outcome
    work
        project contribution
        coaching colleagues
        general improvements
    session
        conference
        bar camp
        meetup
    article
        blog post
        personal diary
```
</div>


---

# Status

<div style="text-align: center">
```mermaid {scale: 1.2}
flowchart LR
    Entered -- pick item --> Started
    Started -- completed\nsuccessfully --> Finished
    Started -- put at rest --> Paused
    Paused -- return to\nitem --> Started
    Paused -- not relevant\nanymore --> Aborted
    Started -- found\nnot useful --> Aborted
    Entered -- priority\ntoo low --> Aborted
```
</div>


---
layout: image-right
image: explosion.png
class: justify-center
---

# But ... how about time?

<img v-click src="https://www.preisparadies.ch/images/source/Uhren/24Stundenuhr/Wanduhr24Stunden.jpg">


---
layout: end
---

# Let's discuss!
