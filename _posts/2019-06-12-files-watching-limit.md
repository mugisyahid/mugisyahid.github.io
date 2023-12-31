---
layout: post
title: "Files Watching Limit"
date: 2019-05-14
description: files watching limit on linux
tags: linux
---

```bash
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```