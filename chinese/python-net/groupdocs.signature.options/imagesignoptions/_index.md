---
title: "ImageSignOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示图像签名选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

表示图像签名选项。

了解更多：
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

ImageSignOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | 使用默认值初始化 ImageSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | 使用图像文件初始化 ImageSignOptions。 |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | 使用图像流初始化新的 ImageSignOptions 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 清除内部资源。 |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | 从 Base64 字符串创建带有预定义图像的新的 ImageSignOptions 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | 图像签名的边框设置。 |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | 签名在文档页上的高度，使用测量值（像素、百分比或毫米；参见 `MeasureType` SizeMeasureType）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | 签名在文档页上的水平对齐方式。 |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | 签名图像的文件路径，仅在未指定 `image_stream` 时使用。 |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | 签名图像流。如果指定，则始终使用它而不是 ImageFilePath。 |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | 签名在文档页上左侧 X 位置的测量值（像素、百分比或毫米）。在未指定水平对齐时有效。参见 `MeasureType` 获取位置测量类型。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | 签名与文档边缘之间的间距。仅在指定水平或垂直对齐时有效。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | 边距的测量类型（像素、百分比或毫米）。 |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | 放置图像在文档上的矩形区域。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | 签名在文档页上的旋转角度（顺时针）。 |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | 形状位置定义形状在文档布局中的呈现位置。仅适用于 Word 文档。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Width 和 Height 属性的测量类型（像素、百分比或毫米）。 |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | 文档页上的拉伸模式。 |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | 签名在文档页上顶部 Y 位置的测量值（像素、百分比或毫米），由 `MeasureType` LocationMeasureType 定义。若未指定垂直对齐则有效。 |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | 签名透明度，范围从 0.0（不透明）到 1.0（透明），默认值为 0（不透明）。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | 签名在文档页面上的垂直对齐方式。 |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | 签名在文档页面上的宽度，以度量值（像素、百分比或毫米 `MeasureType` 大小度量类型）表示。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 签名将放置在所有文档页面上。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 额外的签名外观。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 签名选项的文档类型（`DocumentType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 签名扩展。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 用于加密操作的哈希算法。仅在 PDF 文件的数字签名中受支持。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 用于签名的文档页码。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 指定要签名的页面的选项。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 签名类型（`SignatureType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | 文本签名的 Z 顺序位置，用于确定重叠签名的显示顺序。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # 使用图像文件创建图像签名选项
        options = ImageSignOptions("signature.jpg")
        # 设置签名的位置和大小
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
使用 `ImageSignOptions` 的任务指南：

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
