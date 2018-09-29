# 编辑

原文文档: https://html.spec.whatwg.org/multipage/interaction.html#editing-2

## 6.6 编辑

### 6.6.1 `contenteditable` 内容属性--使得文档局部区域可编辑

```IDL
interface mixin ElementContentEditable {
  [CEReactions] attribute DOMString contentEditable;
  [CEReactions] attribute DOMString enterKeyHint;
  readonly attribute boolean isContentEditable;
  [CEReactions] attribute DOMString inputMode;
};
```
