---
title: HTMLHyperlinkElementUtils.toString()
slug: Web/API/HTMLAnchorElement/toString
tags:
  - HTMLHyperlinkElementUtils.toString()
  - URL API
translation_of: Web/API/HTMLHyperlinkElementUtils/toString
original_slug: Web/API/HTMLHyperlinkElementUtils/toString
---
{{ApiRef("URL API")}}

**`HTMLHyperlinkElementUtils.toString()`** 方法返回一个包含整个 URL 的 {{domxref("USVString")}} 。它是{{domxref("HTMLHyperlinkElementUtils.href")}} 的一个只读版本。

## 句法

```plain
string = object.toString();
```

## 范例

```js
/*
Let's imagine an
<a id="myAnchor" href="https://developer.mozilla.org/en-US/docs/HTMLHyperlinkElementUtils/toString">
 element is in the document
*/
var anchor = document.getElementById("myAnchor");
var result = anchor.toString();
// Returns: 'https://developer.mozilla.org/en-US/docs/HTMLHyperlinkElementUtils/toString'
```

## 规范

{{Specifications}}

## 浏览器兼容性

{{Compat("api.HTMLAnchorElement.toString")}}

## 也可以看看

- The {{domxref("HTMLHyperlinkElementUtils")}} mixin it belongs to.
