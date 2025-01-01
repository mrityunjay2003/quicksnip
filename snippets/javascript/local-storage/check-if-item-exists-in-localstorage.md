---
title: Check if Item Exists in localStorage
description: Checks if a specific item exists in localStorage.
author: axorax
tags: javascript,localStorage,storage,utility
---

```js
const isItemInLocalStorage = (key) => {
  return localStorage.getItem(key) !== null;
};

// Usage:
console.log(isItemInLocalStorage('user')); // Output: true or false
```