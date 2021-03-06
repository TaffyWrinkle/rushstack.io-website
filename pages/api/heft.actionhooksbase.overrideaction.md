---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft](./heft.md) &gt; [ActionHooksBase](./heft.actionhooksbase.md) &gt; [overrideAction](./heft.actionhooksbase.overrideaction.md)

## ActionHooksBase.overrideAction property

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

This hook allows the action's execution to be completely overridden. Only the last-registered plugin with an override hook provided applies.

<b>Signature:</b>

```typescript
readonly overrideAction: AsyncSeriesBailHook<TActionProperties>;
```
