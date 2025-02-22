---
lang: en
title: 'API docs: rest.trie.match'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.trie.match.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [Trie](./rest.trie.md) &gt; [match](./rest.trie.match.md)

## Trie.match() method

Match a route path against the trie

<b>Signature:</b>

```typescript
match(path: string): (ResolvedNode<T> & {
        node: NodeWithValue<T>;
    }) | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  path | string | The route path, such as <code>/customers/c01</code> |

<b>Returns:</b>

([ResolvedNode](./rest.resolvednode.md)<!-- -->&lt;T&gt; &amp; { node: [NodeWithValue](./rest.nodewithvalue.md)<!-- -->&lt;T&gt;; }) \| undefined


