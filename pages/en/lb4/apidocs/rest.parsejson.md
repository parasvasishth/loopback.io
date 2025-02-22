---
lang: en
title: 'API docs: rest.parsejson'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.parsejson.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [parseJson](./rest.parsejson.md)

## parseJson() function

Parse a json string that rejects prohibited keys

<b>Signature:</b>

```typescript
export declare function parseJson(text: string, reviver?: (key: any, value: any) => any, prohibitedKeys?: string[]): any;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  text | string | JSON string |
|  reviver | (key: any, value: any) =&gt; any | <i>(Optional)</i> Optional reviver function for <code>JSON.parse</code> |
|  prohibitedKeys | string\[\] | <i>(Optional)</i> An array of keys to be rejected |

<b>Returns:</b>

any


