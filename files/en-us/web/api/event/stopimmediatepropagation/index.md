---
title: "Event: stopImmediatePropagation() method"
short-title: stopImmediatePropagation()
slug: Web/API/Event/stopImmediatePropagation
page-type: web-api-instance-method
browser-compat: api.Event.stopImmediatePropagation
---

{{APIRef("DOM")}}

The **`stopImmediatePropagation()`** method of the
{{domxref("Event")}} interface prevents other listeners of the same event from being
called.

If several listeners are attached to the same element for the same event type, they are
called in the order in which they were added. If `stopImmediatePropagation()`
is invoked during one such call, no remaining listeners will be called.

## Syntax

```js-nolint
event.stopImmediatePropagation()
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
