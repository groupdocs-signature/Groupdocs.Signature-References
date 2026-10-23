---
title: "TextVerifyOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "保留用于验证文档文本签名的选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

保留用于验证文档文本签名的选项。

了解更多：
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

TextVerifyOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | 使用默认值初始化 TextVerifyOptions 的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | 使用验证文本初始化 TextVerifyOptions 的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | 使用待验证的文本和签名实现类型初始化新的 TextVerifyOptions 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | 要验证的表单字段的标题。如果设置，则仅在文本表单字段中查找该文本。 |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | 要验证的表单字段类型；如果设置，则仅在文本表单字段中查找该文本。 |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | 文本匹配类型的验证。 |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | 要验证的文本签名 ID。必须大于零；仅支持 PDF 文档。 |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | 待验证的签名类型。 |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | 待验证的签名文本。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 指示是否应验证每个文档页面的标志。默认值为 True。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 用于替代签名选项验证的额外扩展。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 有效属性标志。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 要验证的文档页码；如果未设置，则对文档的所有页面进行首次出现的验证（最小值为 1）。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 页面选项用于指定要验证的页面。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | 文档布局中用于在页眉/页脚中验证签名的形状位置。（继承自 [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
使用 `TextVerifyOptions` 的任务指南：

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
