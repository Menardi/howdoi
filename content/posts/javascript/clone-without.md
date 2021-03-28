---
title: "How do I clone an object with a subset of values?"
date: 2021-03-28T14:20:00+01:00
tags: ['javascript']
slug: 'javascript/clone-without'
---

```javascript
const exampleObject = {
  test: 1,
  keyName: 2,
  removeMe: 3,
  hello: 4,
};

const { removeMe, ...newObject } = exampleObject;
```

## Further Reading

 - [Destructuring assignment at MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
