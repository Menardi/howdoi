---
title: "How do I use an object's keys as a type?"
date: 2021-03-28T13:50:00+01:00
tags: ['typescript']
slug: 'typescript/object-keys'
---

```typescript
const exampleObject = {
  test: 1,
  keyName: 2,
  hello: 3
};

type ExampleObjectKeys = keyof typeof exampleObject;
```
