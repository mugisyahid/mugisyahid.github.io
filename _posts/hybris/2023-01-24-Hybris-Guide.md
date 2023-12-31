---
layout: post
title: "Hybris Starter Guide"
date: 2023-01-24
description: Hybris Starter Guide
tags: hybris
---

# [Hybris Starter Guide](http://javainsimpleway.com/hybris-installation/)

1. Extract
1. Go to Installer folder.
```bash
$ ./install.sh -r b2c_acc_plus
```

This command will add the required extensions to the localextensions.xml file as per the recipe name we have provided in the command.



3. Modulegen -> go to bin/platform,

```bash
$  ./setantenv.sh
$ ant modulegen -Dinput.module=accelerator -Dinput.name=training -Dinput.package=com.hybris.training -Dinput.template=develop
```


* module as accelerator which means we are developing B2C module. with module name = training

* java class package prefix, we have given as com.hybris.training

* Template specifies whether configuration is for development or production.



4. `ant clean all`

```bash
sudo spctl --master-disable
```

5. `hybrisserver.(bat/sh) debug`

6. initialization via HAC