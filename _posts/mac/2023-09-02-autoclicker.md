---
layout: post
title: "Mac Auto Cliker"
date: 2023-09-02
description: Mac Auto Cliker
tags: mac
mermaid: true
---


## [Mac Auto Cliker]()


- install cliclick

```bash
brew install cliclick
```

To click at the current mouse location:
```bash
cliclick c:.
```

- apple script

```bash
delay 15
repeat 10 times
    do shell script "/usr/local/bin/cliclick c:."
    delay 1
end repeat
```