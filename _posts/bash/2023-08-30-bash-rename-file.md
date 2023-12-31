---
layout: post
title: "Bash Rename File"
date: 2023-08-30
description: Bash Rename File
tags: bash
mermaid: true
---


## prefix

```bash
for filename in *.jpg; do mv "$filename" "prefix_${filename}"; done;
```


## postfix
```bash
for file in *.java; do mv -- "$file" "${file%.java}Response.java"; done;
```