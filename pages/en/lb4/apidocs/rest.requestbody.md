---
lang: en
title: 'API docs: rest.requestbody'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.requestbody.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [RequestBody](./rest.requestbody.md)

## RequestBody type

Request body with metadata

<b>Signature:</b>

```typescript
export declare type RequestBody = {
    value: any | undefined;
    coercionRequired?: boolean;
    mediaType?: string;
    schema?: SchemaObject | ReferenceObject;
};
```

