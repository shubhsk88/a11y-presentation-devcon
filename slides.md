--- 
theme: seriph
background: transparent
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
colorSchema: light
layout: cover

mdc: true
---



# Accessibility in Design Systems

<v-click>

## Shubham Singh

Frontend Engineer at CDS

</v-click>




---
layout: section
---

# What is Accessibility(A11y)?

Making resources and service usable by everyone

---
transition: slide-up
level: 1
---

# Why A11y is important?

<v-clicks>

- We built it for users 
- Diverse Users
- Different Disablities
- Search Engine Optimization
- Compliance and legislation
  
</v-clicks>
  

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
-  Understandable
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


- Hover
- Click
- Type
- Scroll

</v-clicks>


---
transition: slide-up
level: 2
---

# Multiple Way to access web

<v-clicks>

- Keyboard
- Screen Reader
- Assistive Technologies
- Switch, etc
  
</v-clicks>

<!--
Many users with disabilities rely on keyboard navigation instead of a mouse. When navigating through interactive elements on a webpage using the Tab key, a visible focus indicator helps them understand which element is currently in focus.

Visible focus indicators not only benefit users with disabilities but also improve the overall usability for all users. They provide a visual cue about the user's location and help in navigating the interface efficiently.
-->

---
level: 2
---

# How do user interact with web?


- Hover
- Click
- Type
- Scroll


<v-clicks>

- Tab
- Escape
- Arrow keys
  
</v-clicks>



---
level: 2
transition: slide-up
---
# Use Cases

- Inaccessible Scenario
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

<!--
https://webaim.org/projects/million/
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
5. Color Blindness Emulator
   
</v-clicks>

---
layout: iframe
level: 2
transition: slide-up
url: https://cognitedata.github.io/cogs.js/?path=/story/components-button--base
---

--- 
level: 2
---
# How to include Accessibility?

<v-clicks>

- Integrate the add-on
- Configure the rule in storybook config
- Write all possible stories

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
