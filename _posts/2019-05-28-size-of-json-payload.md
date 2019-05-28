---
layout: post
title: "Size of JSON Payload"
date: 2019-05-28
description: calculate size of JSON Payload
tags: javascript
---

without calculating the "key" size, 


use [sizeof](https://github.com/miktam/sizeof) npm package

and the final touch from [here](https://gist.github.com/zensh/4975495)

```javascript
function formatByteSize(bytes) {
        if(bytes < 1024) return bytes + " bytes";
        else if(bytes < 1048576) return(bytes / 1024).toFixed(3) + " KiB";
        else if(bytes < 1073741824) return(bytes / 1048576).toFixed(3) + " MiB";
        else return(bytes / 1073741824).toFixed(3) + " GiB";
}
```