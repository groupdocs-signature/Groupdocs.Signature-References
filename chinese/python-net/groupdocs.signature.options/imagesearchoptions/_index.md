---
title: "ImageSearchOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示图像签名的搜索选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

表示图像签名的搜索选项。

了解更多：
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

ImageSearchOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | 使用默认值初始化 ImageSearchOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | 搜索条件的图像最大大小（字节）。 |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | 在搜索期间考虑的图像数据的最小大小（字节）。非零值指定最小大小；默认值为零，不影响搜索结果。 |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | 决定是否返回签名的图像内容的标志。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | 返回的图像内容的文件类型，当启用 `return_content` 属性时。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 指示是否在每个文档页上进行搜索的标志。默认值为 True。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 用于搜索的文档页码（可选）。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 指定用于签名搜索的页面的选项。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 指示是否返回文档布局中形状位置的标志。仅适用于 Word 文档。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | 返回仅标记为 `IsSignature` 的签名的标志。默认值为 `False`，表示返回所有符合指定条件的签名。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
