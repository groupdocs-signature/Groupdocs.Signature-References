---
title: "TextSignOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示文本签名选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

表示文本签名选项。

了解更多

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

TextSignOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | 使用默认值初始化 TextSignOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | 使用文本初始化 TextSignOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | 签名背景设置。 |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | 边框设置。 |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | 签名字体。 |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | 签名前景颜色。 |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | 要放置文本签名的文本表单字段的标题。仅当 `signature_implementation` 设置为 `TextSignatureImplementation.FORM_FIELD` 时可使用。 |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | 要放置文本签名的表单字段类型。仅当 `signature_implementation` 设置为 `TextSignatureImplementation.FORM_FIELD`（即 TextToFormField）时此属性适用。默认值为 `FormTextFieldType.ALL_TEXT_TYPES`。 |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | 签名在文档页上的高度，使用测量值（像素、百分比或毫米）。单位由 `SizeMeasureType` 属性决定。 |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | 签名在文档页上的水平对齐方式。 |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | 签名在文档页上的左侧 X 位置，使用测量值（像素、百分比或由 `MeasureType` LocationMeasureType 属性定义的毫米）。在未指定水平对齐时有效。 |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | `left` 和 `top` 属性的测量类型（像素、百分比或毫米）。 |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | 签名与文档边缘之间的间距。仅在指定水平或垂直对齐时适用。 |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | 边距的测量类型（像素、百分比或毫米）。 |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | 本机属性。 |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | 签名在文档页上的旋转角度（顺时针）。 |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | 形状位置定义形状在文档布局中的呈现位置。仅适用于 Word 文档。 |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | 放置文本的形状类型。 |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | 签名的唯一 ID，可在验证选项中使用，仅支持 PDF 文档。 |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | 文本签名实现的类型。 |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Width 和 Height 属性的测量类型（像素、百分比或毫米）。 |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | 文档页面上的拉伸模式。 |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | 签名的文本。 |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | 签名内部文本的水平对齐，仅在 Image 和 Annotation 签名实现中受支持（参见 `TextSignatureImplementation` SignatureImplementation 属性）。 |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | 签名内部文本的垂直对齐方式。 |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | 签名在文档页上的顶部 Y 位置，以测量单位（像素、百分比或毫米）表示。 |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | 签名透明度，取值为 0.0（不透明）到 1.0（透明）之间的浮点数。默认值为 0.0（不透明）。 |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | 签名在文档页面上的垂直对齐方式。 |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | 签名在文档页上的宽度，使用测量值（像素、百分比或毫米；参见 `MeasureType` `SizeMeasureType` 属性）。 |
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
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
使用 `TextSignOptions` 的任务指南：

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
