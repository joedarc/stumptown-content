---
browser-compatibility: html.elements.form.target
specifications: https://html.spec.whatwg.org/multipage/form-control-infrastructure.html#attr-fs-target
---

# `target`

A name or keyword indicating where to display the response that is
received after submitting the form. In HTML 4, this is the
name/keyword for a frame. In HTML5, it is a name/keyword for a
*browsing context* (for example, tab, window, or inline frame).

HTML5: This value can be overridden by a `formtarget` attribute on a
[`<button>`](/en-US/docs/Web/HTML/Element/button)
or
[`<input>`](/en-US/docs/Web/HTML/Element/input)
element.

## Values

### `_self`

Load the response into the same HTML 4 frame (or HTML5
browsing context) as the current one. This value is the default
if the attribute is not specified.

### `_blank`

Load the response into a new unnamed HTML 4 window or HTML5 browsing context.

### `_parent`

Load the response into the HTML 4 `<frameset>` parent of
the current frame, or HTML5 parent browsing context of the
current one. If there is no parent, this option behaves the same
way as `_self`.

### `_top`

HTML 4: Load the response into the full original window,
and cancel all other frames. HTML5: Load the response into the
top-level browsing context (i.e., the browsing context that is
an ancestor of the current one, and has no parent). If there is
no parent, this option behaves the same way as `_self`.

### `iframename`

The response is displayed in a named
[`<iframe>`](/en-US/docs/Web/HTML/Element/iframe).

## Type

String
