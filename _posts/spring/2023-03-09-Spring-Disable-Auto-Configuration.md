---
layout: post
title: "Spring Disable Auto Configuration"
date: 2023-03-09
description: Spring Disable Auto Configuration
tags: spring
---


- annotation
```java
@SpringBootApplication(exclude = {
    MongoAutoConfiguration.class, 
    MongoDataAutoConfiguration.class
})
```

- config file
```
spring.autoconfigure.exclude= \
  org.springframework.boot.autoconfigure.mongo.MongoAutoConfiguration, \
  org.springframework.boot.autoconfigure.data.mongo.MongoDataAutoConfiguration
```