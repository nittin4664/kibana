<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [OnPreAuthToolkit](./kibana-plugin-server.onpreauthtoolkit.md)

## OnPreAuthToolkit interface

A tool set defining an outcome of OnPreAuth interceptor for incoming request.

<b>Signature:</b>

```typescript
export interface OnPreAuthToolkit 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [next](./kibana-plugin-server.onpreauthtoolkit.next.md) | <code>() =&gt; OnPreAuthResult</code> | To pass request to the next handler |
|  [rewriteUrl](./kibana-plugin-server.onpreauthtoolkit.rewriteurl.md) | <code>(url: string) =&gt; OnPreAuthResult</code> | Rewrite requested resources url before is was authenticated and routed to a handler |
