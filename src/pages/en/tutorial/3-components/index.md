---
layout: ~/layouts/TutorialLayout.astro
title: Astro Components
---

## Goals

BY THE END OF THIS SECTION YOU WILL HAVE:
- created reusable Astro components for UI items on your website (e.g. Header, Footer)
- used standard HTML elements alongside Astro components in the same component template
- passed data from one Astro component to another passing `props` as a component attribute
- passed data from one Astro component to another using a `<slot />`
- created a layout template that can be used to render identical elements on multiple pages


Now that you have multiple `.astro` files generating pages on your website, let's explore **component-based design** in Astro to make and reuse smaller bits of HTML!

## Summary
The building blocks of an Astro site are **components**. Astro components are `.astro` files and they generate static HTML. An Astro component can generate the all the HTML needed for an entire web page, like our existing `index.astro`, `about.astro`, and `blog.astro`. Or, they can produce smaller units of HTML that can be included inside other Astro components.

**Component-based design** means building your web page as a collection of modular, often reusable, pieces. Astro components are meant to be building-blocks that can fit within, and alongside other comopnents. In fact, our existing Astro pages are just Astro components that happen to display an entire page's worth of HTML!

## Before You Go

### Test your knowledge

Which of the following could be an Astro component?

a. your website's navigation bar

b. a feedback widget

c. your About page

d. an image

e. ... all of the above, because *any* valid HTML fragment can be generated by an Astro component!


### Checklist for moving on
[ ] I am ready to explore component-based design in Astro!