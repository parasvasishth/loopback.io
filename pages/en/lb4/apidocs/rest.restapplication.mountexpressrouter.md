---
lang: en
title: 'API docs: rest.restapplication.mountexpressrouter'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.restapplication.mountexpressrouter.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [RestApplication](./rest.restapplication.md) &gt; [mountExpressRouter](./rest.restapplication.mountexpressrouter.md)

## RestApplication.mountExpressRouter() method

Mount an Express router to expose additional REST endpoints handled via legacy Express-based stack.

<b>Signature:</b>

```typescript
mountExpressRouter(basePath: string, router: ExpressRequestHandler, spec?: RouterSpec): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  basePath | string | Path where to mount the router at, e.g. <code>/</code> or <code>/api</code>. |
|  router | [ExpressRequestHandler](./express.expressrequesthandler.md) | The Express router to handle the requests. |
|  spec | [RouterSpec](./rest.routerspec.md) | <i>(Optional)</i> A partial OpenAPI spec describing endpoints provided by the router. LoopBack will prepend <code>basePath</code> to all endpoints automatically. This argument is optional. You can leave it out if you don't want to document the routes. |

<b>Returns:</b>

void


