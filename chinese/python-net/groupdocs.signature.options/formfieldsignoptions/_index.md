---
title: "FormFieldSignOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示 PDF 文档的 FormField 签名选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

表示 PDF 文档的 FormField 签名选项。

提供在 PDF 文件中创建或更新表单字段签名的选项。

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

FormFieldSignOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | 使用默认值初始化 PdfFormFieldSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | 使用表单字段签名初始化 PdfFormFieldSignOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | 文档页上签名区域的高度，使用测量单位（像素、百分比或毫米；参见 `MeasureType` SizeMeasureType）。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | 图像在文档页上的水平对齐方式。 |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | 文档页上签名区域的左侧 X 位置，使用测量单位（像素、百分比或毫米）。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Left 和 Top 属性的测量类型（像素、百分比或毫米）。 |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | 图像与文档边缘之间的默认间距（在设置水平或垂直对齐时适用）。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | 边距的测量类型（像素、百分比或毫米）。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | 顺时针测量的旋转角度。 |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | 签名的 FormField。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Width 和 Height 属性的测量类型（像素、百分比或毫米）。 |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | 文档页面上的拉伸模式。 |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | 文档页面上签名区域的顶部 Y 位置，使用测量单位（像素、百分比或毫米）。请参阅 `MeasureType` 了解位置测量类型。 |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | 表单字段签名的透明度。取值范围为 0.0 到 1.0，默认值为 0。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | 图像在文档页上的垂直对齐方式。 |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | 文档页面上签名区域的宽度，以度量值表示（像素、百分比或毫米；参见 `MeasureType` SizeMeasureType）。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | 签名将放置在所有文档页面上。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | 额外的签名外观。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 签名背景设置。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 边框设置。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | 签名选项的文档类型（`DocumentType`）。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | 签名扩展。（继承自 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)） |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 签名字体。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | 签名的前景颜色。（继承自 [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)） |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
