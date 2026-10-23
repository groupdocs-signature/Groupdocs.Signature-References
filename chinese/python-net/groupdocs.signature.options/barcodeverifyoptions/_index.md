---
title: "BarcodeVerifyOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示条形码验证选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodeverifyoptions/
is_root: false
weight: 30
---


## BarcodeVerifyOptions class

表示条形码验证选项。

了解更多
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings

BarcodeVerifyOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/) | 初始化条形码签名的默认验证选项。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text) | 使用验证文本初始化默认验证选项。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#encode_type) | 使用条形码类型验证初始化默认验证选项。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text-encode_type) | 使用条形码类型验证和文本初始化默认验证选项。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/encode_type/) | 用于验证的条形码类型。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 指示是否应验证每个文档页面的标志。默认值为 True。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 用于替代签名选项验证的额外扩展。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | 用于验证的表单字段标题。如果设置，仅在文本表单字段中查找该文本。（继承自 [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)） |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | 用于验证的表单字段类型；如果设置，仅在文本表单字段中查找文本。（继承自 [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)） |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 有效属性标志。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | 文本匹配类型验证。（继承自 [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 要验证的文档页码；如果未设置，则对文档的所有页面进行首次出现的验证（最小值为 1）。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 页面选项用于指定要验证的页面。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | 文档布局中用于在页眉/页脚中验证签名的形状位置。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | 要验证的文本签名 ID。必须大于零；仅支持 PDF 文档。（继承自 [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)） |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | 要验证的签名类型。（继承自 [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)） |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | 要验证的签名文本。（继承自 [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import BarcodeVerifyOptions


def verify_barcode_signatures():
    with Signature("signed.pdf") as signature:
        options = BarcodeVerifyOptions()
        options.all_pages = True
        options.text = "12345"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document was verified successfully: {len(result.succeeded)} matching barcode signature(s).")
        else:
            print("Document failed verification process.")
```

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
