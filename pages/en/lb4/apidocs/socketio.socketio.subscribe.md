---
lang: en
title: 'API docs: socketio.socketio.subscribe'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/extensions/socketio
permalink: /doc/en/lb4/apidocs.socketio.socketio.subscribe.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/socketio](./socketio.md) &gt; [socketio](./socketio.socketio.md) &gt; [subscribe](./socketio.socketio.subscribe.md)

## socketio.subscribe() function

Decorate a method to subscribe to socketio events. For example,

```ts
@socketio.subscribe('chat message')
async function onChat(msg: string) {
}

```

<b>Signature:</b>

```typescript
function subscribe(...messageTypes: (string | RegExp)[]): MethodDecorator;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  messageTypes | (string \| RegExp)\[\] |  |

<b>Returns:</b>

MethodDecorator

