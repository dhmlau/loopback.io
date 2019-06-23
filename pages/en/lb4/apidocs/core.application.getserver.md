---
lang: en
title: 'API docs: core.application.getserver'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.core.application.getserver.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/core](./core.md) &gt; [Application](./core.application.md) &gt; [getServer](./core.application.getserver.md)

## Application.getServer() method

Retrieve the singleton instance for a bound server.

<b>Signature:</b>

```typescript
getServer<T extends Server>(target: Constructor<T> | string): Promise<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  target | <code>Constructor&lt;T&gt; &#124; string</code> |  |

<b>Returns:</b>

`Promise<T>`

A Promise of server instance

