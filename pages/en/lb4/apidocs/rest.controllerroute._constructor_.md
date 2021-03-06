---
lang: en
title: 'API docs: rest.controllerroute._constructor_'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/rest
permalink: /doc/en/lb4/apidocs.rest.controllerroute._constructor_.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [ControllerRoute](./rest.controllerroute.md) &gt; [(constructor)](./rest.controllerroute._constructor_.md)

## ControllerRoute.(constructor)

Construct a controller based route

<b>Signature:</b>

```typescript
constructor(verb: string, path: string, spec: OperationObject, controllerCtor: ControllerClass<T>, controllerFactory?: ControllerFactory<T>, methodName?: string);
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  verb | <code>string</code> | http verb |
|  path | <code>string</code> | http request path |
|  spec | <code>OperationObject</code> | OpenAPI operation spec |
|  controllerCtor | <code>ControllerClass&lt;T&gt;</code> | Controller class |
|  controllerFactory | <code>ControllerFactory&lt;T&gt;</code> | A factory function to create a controller instance |
|  methodName | <code>string</code> | Controller method name, default to <code>x-operation-name</code> |


