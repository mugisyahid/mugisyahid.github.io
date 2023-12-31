---
layout: post
title: "Handy Gradle Command"
date: 2023-03-09
description: Handy Gradle Command
tags: gradle
---


- refresh depedency
```bash
./gradlew build --refresh-dependencies
```

- publish to .m2 local

plugin
```yml
plugins {
    id 'maven-publish'
}
```

```bash
./gradlew publishToMavenLocal
```

- flyway
plugin
```yml
plugins {
    id("org.flywaydb.flyway") version "X.x.x"
}
```
  - migrate
  ```bash
  ./gradlew flywayMigrate
  ```
  - validate
  ```bash
  ./gradlew flywayValidate
  ```