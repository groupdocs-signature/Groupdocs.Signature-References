---
title: "PreviewOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示文档预览选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

表示文档预览选项。

PreviewOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | 预览图像的高度。 |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | 指示签名是否在页面预览图像中隐藏的标志。 |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | 预览图像的页码。 |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | 预览图像的格式。 |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | 预览图像的分辨率，单位为 DPI（每英寸点数）。默认分辨率为 96 DPI。 |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | 预览图像的宽度。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

with Signature("sample.pdf") as signature:
    preview_options = PreviewOptions(create_page_stream)
    preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
    signature.generate_preview(preview_options)
```

### Guides
使用 `PreviewOptions` 的任务指南：

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
