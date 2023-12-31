---
layout: post
title: "Today's Update"
date: 2022-10-07
description: Today's Update
tags: todo
---

### Useful codes


get random mongodb entry

```java
@Aggregation(pipeline={"{$sample:{size:1}}"})
```


aggregation match

```java
@Aggregation(pipeline = {
        "{'$match':{'transaction_type': ?0, 'price' : {$gt : ?1}}",
})
```