---
title: "How do I bring in changes from another branch without merging?"
date: 2021-03-28T14:00:00+01:00
tags: ['git']
slug: 'git/rebase'
---

```bash
git checkout my-branch
git rebase other-branch
```

> Do not rebase if someone else is working on `my-branch` too. It changes the git history so that the commits on `my-branch` will have different commit IDs, and so the other developer's branch will end up in a weird state next time they pull your changes.

## Further Reading

 - [Git Rebase guide by Ben Marshall](https://www.benmarshall.me/git-rebase/)
 - [git rebase official docs](https://git-scm.com/docs/git-rebase)
