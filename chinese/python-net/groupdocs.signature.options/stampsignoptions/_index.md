---
title: "StampSignOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示印章签名选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

表示印章签名选项。

了解更多：
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

StampSignOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | 使用默认值初始化 StampSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | 使用对齐选项初始化 StampSignOptions 类的新实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | 清除内部资源。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | 使用 Base64 字符串中的预定义图像创建新的 ImageSignOptions 实例。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | 印章的背景。 |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | 签名的背景颜色裁剪类型。 |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | 签名的背景图像裁剪类型。 |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | 文档页面上签名区域的高度，使用测量单位（像素、百分比或毫米）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | 图像在文档页上的水平对齐方式。 |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | 内部线条列表，以矩形集合的形式呈现。 |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | 文档页面上签名区域的左侧 X 位置，使用测量单位（像素、百分比或毫米）。参见 `MeasureType` `LocationMeasureType`。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | 默认在图像与文档边缘之间指定的间距（在指定水平或垂直对齐时有效）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | 边距测量类型（像素、百分比或毫米）。 |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | 外部线条列表，以同心圆的形式呈现。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | 顺时针旋转角度。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Width 和 Height 属性的测量类型（像素、百分比或毫米）。 |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | 印章类型。默认是 `Round`。 |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | 文档页上的拉伸模式。 |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | 文档页面上签名区域的顶部 Y 位置，使用测量单位（像素、百分比或毫米）。参见 `MeasureType` `LocationMeasureType`。 |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | 印章签名的透明度。取值范围为 0.0 到 1.0，默认值为 0。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | 印章在文档页面上的垂直对齐方式。 |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | 文档页面上签名区域的宽度，使用测量值（像素、百分比或毫米）。测量单位由 `MeasureType` SizeMeasureType 定义。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 签名将放置在所有文档页面上。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 额外的签名外观。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | 图像签名的边框设置。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 签名选项的文档类型（`DocumentType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 签名扩展。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 用于加密操作的哈希算法。仅在 PDF 文件的数字签名中受支持。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | 签名图像的文件路径，仅在未指定 `image_stream` 时使用。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | 签名图像流。如果指定，则始终替代 ImageFilePath 使用。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 用于签名的文档页码。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 指定要签名的页面的选项。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | 放置图像于文档上的区域矩形。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | 形状位置定义了形状在文档布局中应呈现的位置。仅适用于 Word 文档。（继承自 [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)） |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 签名类型（`SignatureType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | 文本签名的 Z 顺序位置，用于确定重叠签名的显示顺序。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # 根据需要配置额外的印章选项
    signature.sign(options)
```

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
