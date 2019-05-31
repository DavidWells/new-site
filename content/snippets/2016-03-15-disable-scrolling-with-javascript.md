---
title: Disable Scrolling with JavaScript
author: David Wells
date: 2016-03-15
layout: post
tags:
  - javascript
---

Handy for modals and other cases where you don't want the user to be able to scroll

```js
function noScroll() {
  window.scrollTo( 0, 0 );
}

// add listener to disable scroll
window.addEventListener('scroll', noScroll);

// Remove listener to disable scroll
window.removeEventListener('scroll', noScroll);

```