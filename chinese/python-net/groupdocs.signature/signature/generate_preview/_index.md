---
title: "generate_preview 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "生成文档页面预览。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

生成文档页面预览。

了解更多关于如何为文档页面生成预览的信息：
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| preview_options | `PreviewOptions` | 预览选项。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # 页码从 0 开始计数：preview_page_0.png 是第一页
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
