---
lang: en
title: 'API docs: context.contextview.observe'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/context
permalink: /doc/en/lb4/apidocs.context.contextview.observe.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [ContextView](./context.contextview.md) &gt; [observe](./context.contextview.observe.md)

## ContextView.observe() method

Listen on `bind` or `unbind` and invalidate the cache

<b>Signature:</b>

```typescript
observe(event: ContextEventType, binding: Readonly<Binding<unknown>>, context: Context): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  event | [ContextEventType](./context.contexteventtype.md) |  |
|  binding | Readonly&lt;[Binding](./context.binding.md)<!-- -->&lt;unknown&gt;&gt; |  |
|  context | [Context](./context.context.md) |  |

<b>Returns:</b>

void


