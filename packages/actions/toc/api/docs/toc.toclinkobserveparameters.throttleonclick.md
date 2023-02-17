<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@svelte-put/toc](./toc.md) &gt; [TocLinkObserveParameters](./toc.toclinkobserveparameters.md) &gt; [throttleOnClick](./toc.toclinkobserveparameters.throttleonclick.md)

## TocLinkObserveParameters.throttleOnClick property

throttle the observe of `use:toc` on click

**Signature:**

```typescript
throttleOnClick?: number;
```

## Remarks

This ensures that the active toc item will be the same one that this link is pointing to. Otherwise, it is not guaranteed so, because `observe` is handled with `IntersectionObserver` the next items might already comes into viewport when this link is clicked.

Set to 0 to disable throttling.

Default to: `500`
