---
layout: post
title: "ReferencePipeline Exception"
date: 2023-08-20
description: ReferencePipeline Exception
tags: java bug
mermaid: true
---


## java streams java.util.stream.ReferencePipeline Exception

need .flatMap(Collection::stream)

```java

    projects.stream()
            .map(Project::getGroups)
            .flatMap(Collection::stream)
            .map(Group::getStudents)
            .flatMap(Collection::stream)
            .map(Student::getName)
            .collect(toList());

```
