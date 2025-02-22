---
lang: en
title: 'API docs: repository.constructorfunction'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.constructorfunction.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [ConstructorFunction](./repository.constructorfunction.md)

## ConstructorFunction interface

Interface for constructor functions without `new` operator.

<b>Signature:</b>

```typescript
export interface ConstructorFunction<T> 
```

## Example


```ts
function Foo(x) {
  if (!(this instanceof Foo)) { return new Foo(x); }
  this.x = x;
}
```


