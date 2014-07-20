---
layout: post
title: "GitHub notes"
date: 2013-12-01 18:40:02 +0400
comments: true
categories:
---

Syncing a fork
```bash
git remote add upstream https://github.com/otheruser/repo.git
git fetch upstream
git checkout master
git merge upstream/master
git push
```

Syncing a fork & drop local changes
```bash
git reset --hard HEAD~1
git push origin +master
```
