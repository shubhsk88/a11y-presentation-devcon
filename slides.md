---
theme: bricks
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
author: Shubham Singh
keywords: A11y, Accessibility, Design System
info: |
  ## Accessibility in Design system
 


drawings:
  persist: false
transition: slide-left

mdc: true
---



# Accessibility in Design Systems

<v-click>

## Shubham Singh

Frontend Engineer at CDS

</v-click>


---

# Table of contents

<Toc maxDepth="1"></Toc>

---
layout: section
---

# What is Accessibility?

Making resources and service usable by everyone

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
transition: slide-up
level: 1
---

# Why A11y is important?

- We built it for users
- Search Engine Optimization
- Compliance and legislation
- Diverse Users
- Different Disablities
  

[^1]: [Learn More](https://sli.dev/guide/syntax.html#line-highlighting)

<style>
.footnotes-sep {
  @apply mt-20 opacity-10;
}
.footnotes {
  @apply text-sm opacity-75;
}
.footnote-backref {
  display: none;
}
</style>
--- 
transition: slide-up
level: 2
---

# A11y Principles

- Perceivable
-  Operable
-  Understanble
-  Robust

<!--
This principle states that users must be able to perceive all essential information on the screen, and it must be conveyed to multiple senses.
users must be able to operate the digital product's interface. The interface cannot require interaction that a user cannot perform.
This principle focuses on supporting assistive technologies and ensuring that, as devices and user agents evolve, the digital product remains accessible

Perceivable->Ensuring color is not the only method of conveying meaning.
OPerable-> Adding keyboard and touchscreen support to all active elements.
Understandable-> Ensuring error messages are clear and easy to resolve
Robust-> Testing keyboard-only navigation.
Testing with different screen reader technologies.
-->

---
layout: two-cols
level: 2
---

# Type of Disabilities

- Visual Impairments
- Mobile Impairments
- Hearing Impairments
- Cognitive impairments
- Speech impairments

::right::
<div class="flex justify-center aligns-center ">
<img src="/groups.png" class="w-xs" />
</div>

<!--
B/blindness, low vision, color blindness
Digital products that do not work with screen reader software, mobile websites/apps without pinch to zoom, complex graphs and charts differentiated by colors alone,

Mobility->Elements that are only designed to work with the use of a mouse.

Hearing-> D/deafness, hard of hearing (HoH), hearing impaired (HI
Content without transcript

 Down's syndrome, A/autism, ADHD, dyslexia, aphasia.
Busy interfaces that make it overly complicated to focus on the task at hand, big walls of words with little whitespace, justified text, and small or hard-to-read fonts.
-->

---
transition: slide-up
---

# How do user interact with web?

<v-clicks>
<div class="hover-item" >Hover</div>
<div class="click-item" >Click</div>
<div class="type-item" >Type</div>
<div class="scroll-item" >Scroll</div> 

</v-clicks>

<style>
.hover-item{
  position:absolute;
  top:30rem;
  left:10rem; 
}
.click-item{
 position:absolute;
 top:10rem;
 left:40rem;
}
.type-item{
  position:absolute;
  top:20rem;
  right:30rem;
}
.scroll-item{
  position:absolute;
  bottom:50px;
  right:30rem;
}
.tab-item{
  position:absolute;
  top:70px;
  left:40vw;

}

  </style>

---
transition: slide-up
depth: 2
---

# Multiple Way to access web

<v-clicks>

- Screen Reader
- Assistive Technologies
- Braile
- Switch, etc
  
</v-clicks>

---
level: 2
---

# How do user interact with web?

<v-clicks>
<div class="hover-item" >Hover</div>
<div class="click-item" >Click</div>
<div class="type-item" >Type</div>
<div class="scroll-item" >Scroll</div> 
<div class="tab-item absolute bottom-40 right-60">Tab</div>
<div class="escape-item absolute top-40 right-50">Escape</div>
<div class="arrow-item absolute top-80 left-50">Arrow keys</div>
</v-clicks>

<style>
.hover-item{
  position:absolute;
  top:30rem;
  left:10rem; 
}
.click-item{
 position:absolute;
 top:10rem;
 left:40rem;
}
.type-item{
  position:absolute;
  top:20rem;
  right:30rem;
}
.scroll-item{
  position:absolute;
  bottom:50px;
  right:30rem;
}
.type-item{
  position:absolute;
  top:20rem;
  right:30rem;
}
.scroll-item{
  position:absolute;
  bottom:50px;
  right:30rem;
}


  </style>

---
level: 2
transition: slide-up
---
# Format

- InAccessible Scenario
- The Fix
- Accessible behaviour

---
level: 2
transition: slide-up
layout: center
---

# Scenario: Button

<!--
If we have action to do we should use button, but if we are navigation to somewhere else we use anchor link
-->

---
level: 2
layout: center
transition: slide-up
---

# Scenario: Forms

---
level: 2
transition: slide-up
layout: center
---

# Scenario: Dynamic Information

<!--
Example of toast and showing error messages in form and showing form error page
-->

---
level: 2
transition: slide-up
layout: center
---

# Scenario: Modal and Drawer

<!--
https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/examples/dialog/
https://developer.mozilla.org/en-US/docs/Web/API/HTMLDialogElement/showModal
https://explore-a11y.netlify.app/modal
-->

---
level: 2
transition: slide-up
layout: center
---

# Scenario: Nested Interactive Elements

--- 
layout: center
transition: slide-up
level: 2
---
<img src="/slack-message.png"/> 

---
level: 2
---

# Google Use case

 <img src="/google-usecase.png"/>


---
transition: slide-up
--- 

# Testing Accessibility

 
- Page based
- Component Based
  
---
layout: section 
level: 2
transition: slide-up

---

# Storybook A11y add-on

A tool that helps to identify and address accessibility issues in UI components.


---
transition: slide-up
level: 2
---
# Why Storybook A11y addon?

<v-clicks>

1. Easy Integration
2. Part of golden path
3. Effective Feedback
4. Flexibility
5. Color Blindness
   
</v-clicks>

---
layout: iframe
level: 2
transition: slide-up
url: https://cognitedata.github.io/cogs.js/?path=/story/components-inputexp--base
---

--- 
level: 2
---
# How to include Accessibility?

<v-clicks>

- Integrate the add-on
- Configure the rule in storybook config
- Write all possible stories
- Write all possible interaction tests

</v-clicks>
   


---
layout: two-cols
---
# Summary

- Use semantic HTML
- Don't remove outline
- Text description for interactive elements
- Dynamic messages in toast and alert should be announced

::right::
<img src="/header-meme.png"/>

---

# More Resources

- [Inclusive Component Design](https://inclusive-components.design/)
- [Learn Accessibility](https://web.dev/learn/accessibility)
- [React Aria](https://react-spectrum.adobe.com/react-aria/)
- [The A11y Project](https://www.a11yproject.com/)

---
layout: cover
level: 2
background: https://source.unsplash.com/collection/94734566/1920x1080
---

# Thank You

## Questions?
