---
title: "QrCodeSignOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示 QR 码签名选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

表示 QR 码签名选项。

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

QrCodeSignOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | 使用默认值初始化 QRCodeSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | 使用指定的文本初始化 QR 码签名选项实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | 使用文本初始化 QrCodeSignOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | 生成的 QR-code 图像中文本的对齐方式，默认值为 None。 |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | 用于序列化为 QR-Code 内容的自定义对象。 |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | 用于对 QR 码签名文本或数据进行编码和解码的数据加密实现。 |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | QR-Code 类型。 |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | QR 码条的前景色；使用此属性可能导致验证问题，请谨慎使用。 |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | 文档页上签名区域的高度，使用测量单位（像素、百分比或毫米；参见 `MeasureType` SizeMeasureType）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | 文档页面上 QR 码的水平对齐方式。 |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | QR 码元素与生成图像边框之间的间距。 |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | 文档页面上签名区域左侧 X 位置，使用测量单位（像素、百分比或毫米）。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | QR-code 徽标图像文件名。 |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | QR-code 徽标图像流。 |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | 默认在图像和文档边缘之间指定的间距（在指定水平或垂直对齐时生效）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | 边距测量类型（像素、百分比或毫米）。 |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | 用于检索放置在文档页面上的签名的 QR-Code 图像内容的标志。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | 当启用 `return_content` 属性时，返回的 QR‑Code 签名图像内容的文件类型。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | 顺时针方向的旋转角度（单位：度）。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Width 和 Height 属性的测量类型（像素、百分比或毫米）。 |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | 文档页上的拉伸模式。 |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | 文档页面上签名区域顶部 Y 位置，使用测量单位（像素、百分比或毫米）。单位由 `MeasureType` 类型的 `LocationMeasureType` 属性定义。 |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | QR 码签名的透明度。取值范围为 0.0 到 1.0，默认值为 0。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | 图像在文档页上的垂直对齐方式。 |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | 文档页面上签名区域的宽度，使用测量值（像素、百分比或由 `MeasureType` 定义的毫米）。 |
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
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 将文本和 QR 码类型传递给构造函数
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # 将 QR 码放置在页面的右下角
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 模块颜色、背景以及带有内部间距的点状边框
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
使用 `QrCodeSignOptions` 的任务指南：

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
