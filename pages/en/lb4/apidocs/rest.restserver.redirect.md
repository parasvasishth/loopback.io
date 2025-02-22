---
lang: en
title: 'API docs: rest.restserver.redirect'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.restserver.redirect.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [RestServer](./rest.restserver.md) &gt; [redirect](./rest.restserver.redirect.md)

## RestServer.redirect() method

Register a route redirecting callers to a different URL.

<b>Signature:</b>

```typescript
redirect(fromPath: string, toPathOrUrl: string, statusCode?: number): Binding;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fromPath | string | URL path of the redirect endpoint |
|  toPathOrUrl | string | Location (URL path or full URL) where to redirect to. If your server is configured with a custom <code>basePath</code>, then the base path is prepended to the target location. |
|  statusCode | number | <i>(Optional)</i> HTTP status code to respond with, defaults to 303 (See Other). |

<b>Returns:</b>

[Binding](./context.binding.md)

## Example


```ts
server.redirect('/explorer', '/explorer/');
```


