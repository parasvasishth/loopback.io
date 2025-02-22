---
lang: en
title: 'API docs: repository.typeresolver'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.typeresolver.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [TypeResolver](./repository.typeresolver.md)

## TypeResolver type

A type resolver is a function that returns a class representing the type, typically a Model or Entity (e.g. Product).

We use type resolvers to break require() loops when defining relations. The target model (class) is provided via a provider, thus deferring the actual reference to the class itself until later, when both sides of the relation are created as JavaScript classes.

<b>Signature:</b>

```typescript
export declare type TypeResolver<Type extends Object, StaticMembers = Function> = () => Class<Type> & StaticMembers;
```
<b>References:</b> [Class](./repository.class.md)


