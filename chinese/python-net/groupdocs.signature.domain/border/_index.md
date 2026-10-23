---
title: "Border 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示边框外观。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

表示边框外观。

Border 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | 实现 IClonable 接口。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | 签名的边框颜色。 |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | 签名边框样式。 |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | 签名边框透明度，范围从 0.0（不透明）到 1.0（透明），默认值为 0（不透明）。 |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | 边框的可见性。 |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | 签名边框的粗细。 |

### 示例

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
使用 `Border` 的任务指南：

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
