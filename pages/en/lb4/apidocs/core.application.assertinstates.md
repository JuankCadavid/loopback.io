---
lang: en
title: 'API docs: core.application.assertinstates'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/core
permalink: /doc/en/lb4/apidocs.core.application.assertinstates.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/core](./core.md) &gt; [Application](./core.application.md) &gt; [assertInStates](./core.application.assertinstates.md)

## Application.assertInStates() method

Assert current state of the application to be one of the expected values

<b>Signature:</b>

```typescript
protected assertInStates(op: string, ...states: string[]): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  op | <code>string</code> | The operation name, such as 'boot', 'start', or 'stop' |
|  states | <code>string[]</code> | Valid states |

<b>Returns:</b>

`void`

