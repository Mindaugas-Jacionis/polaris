---
title: shadow/function-disallowed-list
description: Disallows use of built-in and legacy shadow functions.
keywords:
  - stylelint
  - shadow
  - shadow rules
---

```diff
// Do
+ box-shadow: var(--p-shadow-md);
// Don't
- filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.1));
```