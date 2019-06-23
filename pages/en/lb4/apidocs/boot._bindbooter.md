---
lang: en
title: 'API docs: boot._bindbooter'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.boot._bindbooter.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/boot](./boot.md) &gt; [\_bindBooter](./boot._bindbooter.md)

## \_bindBooter() function

Method which binds a given Booter to a given Context with the Prefix and Tags expected by the Bootstrapper

<b>Signature:</b>

```typescript
export declare function _bindBooter(ctx: Context, booterCls: Constructor<Booter>): Binding;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  ctx | <code>Context</code> | The Context to bind the Booter Class |
|  booterCls | <code>Constructor&lt;Booter&gt;</code> | Booter class to be bound |

<b>Returns:</b>

`Binding`

