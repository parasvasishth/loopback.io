---
lang: en
title: 'API docs: repository.kvconnector.get'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.kvconnector.get.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [KVConnector](./repository.kvconnector.md) &gt; [get](./repository.kvconnector.get.md)

## KVConnector.get() method

Get an entry by key

<b>Signature:</b>

```typescript
get(modelClass: Class<Entity>, key: string, options?: Options): Promise<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modelClass | [Class](./repository.class.md)<!-- -->&lt;[Entity](./repository.entity.md)<!-- -->&gt; | Model class |
|  key | string | Key for the entry |
|  options | [Options](./repository.options.md) | <i>(Optional)</i> Options for the operation |

<b>Returns:</b>

Promise&lt;T&gt;

A promise of the entry found for the key


