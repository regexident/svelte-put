<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@svelte-put/toc](./toc.md) &gt; [TocLinkObserveParameters](./toc.toclinkobserveparameters.md) &gt; [attribute](./toc.toclinkobserveparameters.attribute.md)

## TocLinkObserveParameters.attribute property

boolean attribute(s) to indicate if this is linking to the active toc item

**Signature:**

```typescript
attribute?: string | string[] | boolean;
```

## Remarks

For this to work, it is required that `tocItem` be provided or the href is in the form `'#<toc-item-id>'`

By default, `toclink` uses [MutationObserver](https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver) . For better performance, provide `store`

Set `false` to disable this behavior

Default to: `'data-toc-link-active'`
