---
title: '<dt>: The Description Term element'
short_title: <dt>
mdn_url: /en-US/docs/Web/HTML/Element/dt
specifications: https://html.spec.whatwg.org/multipage/grouping-content.html#the-dt-element
tags:
    group: Text content
api: HTMLElement
permitted_aria_roles: none
tag_omission: yes
interactive_example:
    url: https://interactive-examples.mdn.mozilla.net/pages/tabbed/dt.html
    height: html-standard
browser_compatibility: html.elements.dt
examples:
    - examples/link-to-examples
attributes:
    global: /content/html/global_attributes
recipe: html-element
---

## Short description

The **HTML `<dt>` element** specifies a term in a description or
definition list, and as such must be used inside a
[`<dl>`](/en-US/docs/Web/HTML/Element/dl)
element.

## Overview

It is usually followed by a
[`<dd>`](/en-US/docs/Web/HTML/Element/dd)
element; however, multiple `<dt>` elements in a row indicate several
terms that are all defined by the immediate next
[`<dd>`](/en-US/docs/Web/HTML/Element/dd)
element.

The subsequent
[`<dd>`](/en-US/docs/Web/HTML/Element/dd)
(**Description Details**) element provides the definition or other
related text associated with the term specified using `<dt>`.

## See also

- [`<dd>`](/en-US/docs/Web/HTML/Element/dd),
  [`<dl>`](/en-US/docs/Web/HTML/Element/dl)
