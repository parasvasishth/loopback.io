---
lang: en
title: 'API docs: repository.prototypeof'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.prototypeof.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [PrototypeOf](./repository.prototypeof.md)

## PrototypeOf type

Type helper to infer prototype from a constructor function.

Example: `PrototypeOf<typeof Entity>` is resolved to `Entity`<!-- -->.

<b>Signature:</b>

```typescript
export declare type PrototypeOf<Ctor extends Function> = Ctor extends {
    prototype: infer Proto;
} ? Proto : never;
```

