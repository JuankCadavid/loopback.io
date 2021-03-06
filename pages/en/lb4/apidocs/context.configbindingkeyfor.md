---
lang: en
title: 'API docs: context.configbindingkeyfor'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/context
permalink: /doc/en/lb4/apidocs.context.configbindingkeyfor.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [configBindingKeyFor](./context.configbindingkeyfor.md)

## configBindingKeyFor() function

Create binding key for configuration of the binding

<b>Signature:</b>

```typescript
export declare function configBindingKeyFor<ConfigValueType = unknown>(key: BindingAddress, propertyPath?: string): BindingKey<ConfigValueType>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  key | <code>BindingAddress</code> | Binding key for the target binding |
|  propertyPath | <code>string</code> | Property path for the configuration |

<b>Returns:</b>

`BindingKey<ConfigValueType>`


