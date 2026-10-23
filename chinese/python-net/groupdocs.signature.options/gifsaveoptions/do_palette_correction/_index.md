---
title: "do_palette_correction 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "指示是否应用调色板校正的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

指示是否应用调色板校正的标志。

调色板校正指的是每当图像导出为 GIF 时，源图像的颜色将被分析，以构建最匹配的调色板（如果图像调色板不存在或在选项中未指定）。分析过程需要一些时间；然而，输出图像将拥有最佳匹配的颜色调色板，视觉效果更佳。

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### 另见
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
