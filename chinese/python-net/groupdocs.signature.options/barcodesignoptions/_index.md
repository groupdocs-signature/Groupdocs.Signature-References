---
title: "BarcodeSignOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示条形码签名选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

表示条形码签名选项。

了解更多

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

BarcodeSignOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | 使用默认值初始化 BarcodeSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | 使用文本初始化 BarcodeSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | 使用文本初始化 BarcodeSignOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | 结果条形码图像中文本的对齐方式。默认值为 None。 |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | 条形码类型。 |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | 条形码条的前景色；使用它可能导致验证问题，请谨慎使用。 |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | 文档页面上签名区域的高度，使用测量单位（像素、百分比或毫米）。请参阅 `MeasureType` 了解尺寸测量类型。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | 图像在文档页上的水平对齐方式。 |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | 条形码元素与结果图像边框之间的间距。 |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | 文档页面上签名区域的左侧 X 位置，以测量单位（像素、百分比或毫米）表示。请参阅 `MeasureType`。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | 默认情况下图像与文档边缘之间的间距（在设置水平或垂直对齐时适用）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | 边距测量类型（像素、百分比或毫米）。 |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | 标志指示是否检索放置在文档页面上的签名的条形码图像内容。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | 当启用 `return_content` 属性时，返回的条形码签名图像内容的文件类型。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | 顺时针旋转角度。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Width 和 Height 属性的测量类型（像素、百分比或毫米）。 |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | 文档页上的拉伸模式。 |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | 文档页面上签名区域的顶部 Y 位置，使用测量单位（像素、百分比或毫米）。请参阅 `MeasureType` LocationMeasureType。 |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | 条形码签名的透明度，范围从 0.0（完全不透明）到 1.0（完全透明）；默认值为 0。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | 文档页面上条形码图像的垂直对齐方式。 |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | 文档页面上签名区域的宽度，以度量值（像素、百分比或毫米）表示，由 `MeasureType` 定义。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 签名将放置在所有文档页面上。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 额外的签名外观。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 签名背景设置。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 边框设置。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 签名选项的文档类型（`DocumentType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 签名扩展。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 签名字体。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | 用于放置文本签名的文本表单字段的标题。仅当 `signature_implementation` 设置为 `TextSignatureImplementation.FORM_FIELD` 时可使用。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | 用于放置文本签名的表单字段类型。仅当 `signature_implementation` 设置为 `TextSignatureImplementation.FORM_FIELD`（即 TextToFormField）时此属性适用。默认值为 `FormTextFieldType.ALL_TEXT_TYPES`。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | 用于加密操作的哈希算法。仅在 PDF 文件的数字签名中受支持。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | 本机属性。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | 用于签名的文档页码。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | 指定要签名的页面的选项。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | 形状位置定义了形状在文档布局中的呈现位置。仅适用于 Word 文档。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | 用于放置文本的形状类型。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | 签名的唯一 ID，可在验证选项中使用，仅支持 PDF 文档。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | 文本签名实现的类型。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | 签名类型（`SignatureType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | 签名的文本。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | 签名内部文本的水平对齐方式，仅在 Image 和 Annotation 签名实现中受支持（参见 `TextSignatureImplementation` 的 SignatureImplementation 属性）。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | 签名内部文本的垂直对齐方式。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | 文本签名的 Z 顺序位置，用于确定重叠签名的显示顺序。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
使用 `BarcodeSignOptions` 的任务指南：

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
