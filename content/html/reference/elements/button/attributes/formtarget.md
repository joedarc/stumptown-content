---
browser-compatibility: html.elements.button.formtarget
specifications: https://html.spec.whatwg.org/multipage/form-control-infrastructure.html#attr-fs-formtarget
---

# `formtarget`

If the button is a submit button, this attribute is a name or
keyword indicating where to display the response that is received
after submitting the form. This is a name of, or keyword for, a
*browsing context* (for example, tab, window, or inline frame). If
this attribute is specified, it overrides the `target` attribute of
the button's form owner.

The following keywords have special
meanings:
- `_self`: Load the response into the same browsing context as the
  current one. This value is the default if the attribute is not
  specified.
- `_blank`: Load the response into a new unnamed browsing context.
- `_parent`: Load the response into the parent browsing context of
  the current one. If there is no parent, this option behaves the
  same way as `_self`.
- `_top`: Load the response into the top-level browsing context
  (that is, the browsing context that is an ancestor of the
  current one, and has no parent). If there is no parent, this
  option behaves the same way as `_self`.

## Type

String
