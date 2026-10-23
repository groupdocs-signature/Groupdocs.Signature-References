---
title: "StampLine 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "指定印章线属性。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

指定印章线属性。

StampLine 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | 使用默认值初始化 StampLine。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | 签名的背景颜色。 |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | 印章行文本的字体。 |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | 印章上的行高。 |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | 印章行的内部边框。 |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | 印章线的外边框。 |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | 印章线的文本。 |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | 文本的底部意图。 |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | 签名的文本颜色。 |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | 文本重复类型。 |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | 印章线的可见性。 |

### 示例

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# 创建印章线
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
