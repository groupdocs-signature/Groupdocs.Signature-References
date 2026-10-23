---
title: "pixel_aspect_ratio 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "GIF 像素宽高比。"
type: docs
url: /zh/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

GIF 像素宽高比。

像素宽高比 – 用于计算原始图像中像素宽高比近似值的因子。如果该字段的值不为 0，则根据以下公式计算该宽高比的近似值：

宽高比 = (Pixel Aspect Ratio + 15) / 64

像素宽高比定义为像素宽度除以高度的商。此字段的取值范围允许以 1/64 为增量指定最宽像素为 4:1，最窄像素为 1:4。

值：
- 0 – No aspect ratio information is given.
- 1..255 – Value used in the computation.

### Definition:
```python
@property
def pixel_aspect_ratio(self):
    ...
@pixel_aspect_ratio.setter
def pixel_aspect_ratio(self, value):
    ...
```

### 另见
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
