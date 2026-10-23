---
title: "SignatureFont 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "SignatureFont 类指定文本签名的字体属性。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

SignatureFont 类指定文本签名的字体属性。

SignatureFont 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | 使用默认值初始化 SignatureFont。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | 字体粗体样式。 |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | 字体族名称。 |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | 字体斜体样式。 |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | 字体大小。 |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | 字体删除线样式。 |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | 字体下划线样式。 |

### 示例

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
使用 `SignatureFont` 的任务指南：

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
