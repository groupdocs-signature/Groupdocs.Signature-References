---
title: "color_resolution 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "GIF 颜色分辨率。"
type: docs
url: /zh/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

GIF 颜色分辨率。

颜色分辨率 - 原始图像每个原色可用的位数减 1。此值表示用于选择图形颜色的整个调色板的大小，而不是图形实际使用的颜色数量。例如，如果此字段的值为 3，则原始图像的调色板每个原色有 4 位可用于创建图像。即使源机器并未提供整个调色板的所有颜色，也应设置此值以指示原始调色板的丰富程度。

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### 另见
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
