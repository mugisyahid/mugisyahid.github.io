---
layout: post
title: "Hybris Interceptor"
date: 2022-06-07
description: Interceptor for different lifecycle of ModelService
tags: hybris
mermaid: true
---


<div class="mermaid">
---
title: interceptor
---
flowchart TD

</div>

## How to
- create Interceptor class `XInterceptor<XObject>`
- update bean
```xml
<bean id="..." class="..." />
```
- create bean mapping
```xml
<bean id="..." class="...">
    <property name="interceptor" ref="beanInterceptor">
    <property name="typeCode" ref="XObject">
</bean>
```


interceptor for model lifecycle are:

- InitDefaultsInterceptor

This Interceptor is called when we create a new model filled with its default values calling modelService.initDefaults() or modelService.create(). 

- PrepareInterceptor

This Interceptor is called before a model is saved to the database(modelService.save()) and before it is validated by Validate interceptors.

- ValidateInterceptor

This Interceptor is called before a model is saved to the database(modelService.save()) after is been prepared by the Prepare interceptors,. You can use Validate Interceptors to validate values of the model and raise an InterceptorException if any values are not valid. An exception raised during execution prevents the model from being saved.

- LoadInterceptor

This Interceptor is called after a model is retrieved from the database using modelService.get().

- RemoveInterceptor

This Interceptor is called before a model is removed from the database using modelService.remove(). 


## disable interceptor

- via code
```java
final Map<String, Object> params = ImmutableMap.of(InterceptorExecutionPolicy.DISABLED_INTERCEPTOR_BEANS, ImmutableSet.of("beanInterceptor"));

  getSessionService().executeInLocalViewWithParams(params, new SessionExecutionBody()
  {
   @Override
   public void executeWithoutResult()
   {
   }
  });
```

- via impex in the header
```impex
INSERT header[disable.interceptor.types=validate]
```