---
lang: en
title: 'API docs: core.application.onstart'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/core
permalink: /doc/en/lb4/apidocs.core.application.onstart.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/core](./core.md) &gt; [Application](./core.application.md) &gt; [onStart](./core.application.onstart.md)

## Application.onStart() method

Register a function to be called when the application starts.

This is a shortcut for adding a binding for a LifeCycleObserver implementing a `start()` method.

<b>Signature:</b>

```typescript
onStart(fn: () => ValueOrPromise<void>): Binding<LifeCycleObserver>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fn | () =&gt; [ValueOrPromise](./context.valueorpromise.md)<!-- -->&lt;void&gt; | The function to invoke, it can be synchronous (returning <code>void</code>) or asynchronous (returning <code>Promise&lt;void&gt;</code>). |

<b>Returns:</b>

[Binding](./context.binding.md)<!-- -->&lt;[LifeCycleObserver](./core.lifecycleobserver.md)<!-- -->&gt;

The LifeCycleObserver binding created.


