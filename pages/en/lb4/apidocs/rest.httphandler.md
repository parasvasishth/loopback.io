---
lang: en
title: 'API docs: rest.httphandler'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/loopbackio/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.httphandler.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [HttpHandler](./rest.httphandler.md)

## HttpHandler class

<b>Signature:</b>

```typescript
export declare class HttpHandler 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(\_rootContext, \_serverConfig, \_routes)](./rest.httphandler._constructor_.md) |  | Constructs a new instance of the <code>HttpHandler</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [\_openApiComponents](./rest.httphandler._openapicomponents.md) | <code>protected</code> | ComponentsObject | Shared OpenAPI spec objects as <code>components</code> |
|  [\_rootContext](./rest.httphandler._rootcontext.md) | <p><code>protected</code></p><p><code>readonly</code></p> | [Context](./context.context.md) |  |
|  [\_routes](./rest.httphandler._routes.md) | <p><code>protected</code></p><p><code>readonly</code></p> | [RoutingTable](./rest.routingtable.md) |  |
|  [\_serverConfig](./rest.httphandler._serverconfig.md) | <p><code>protected</code></p><p><code>readonly</code></p> | [RestServerResolvedConfig](./rest.restserverresolvedconfig.md) |  |
|  [handleRequest](./rest.httphandler.handlerequest.md) |  | (request: Request, response: Response) =&gt; Promise&lt;void&gt; |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [\_handleRequest(request, response)](./rest.httphandler._handlerequest.md) | <code>protected</code> |  |
|  [describeApiPaths()](./rest.httphandler.describeapipaths.md) |  |  |
|  [findRoute(request)](./rest.httphandler.findroute.md) |  |  |
|  [getApiComponents()](./rest.httphandler.getapicomponents.md) |  |  |
|  [getApiDefinitions()](./rest.httphandler.getapidefinitions.md) |  |  |
|  [registerApiComponents(defs)](./rest.httphandler.registerapicomponents.md) |  | Merge components into the OpenApi spec |
|  [registerApiDefinitions(defs)](./rest.httphandler.registerapidefinitions.md) |  |  |
|  [registerController(spec, controllerCtor, controllerFactory)](./rest.httphandler.registercontroller.md) |  |  |
|  [registerRoute(route)](./rest.httphandler.registerroute.md) |  |  |


