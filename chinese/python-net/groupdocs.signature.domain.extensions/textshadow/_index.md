---
title: "TextShadow 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示文本签名的文字阴影属性。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/textshadow/
is_root: false
weight: 380
---


## TextShadow class

表示文本签名的文字阴影属性。

结果可能因签名类型和文档格式而异。

建议在所有受支持的文档类型中将 TextShadow 与 `TextAsImage` 签名一起使用，也可与简单的 [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) 和 [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) 作为电子表格（`.xslx`）和演示文稿（`.pptx`）的水印一起使用。

对于 Word 文档（`.docx`），也推荐使用简单的[`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/)，但功能有限。

TextShadow 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/__init__/) | 使用默认选项初始化 TextShadow。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | 获取此对象的副本。（继承自 [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [angle](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/angle/) | 相对于文本放置阴影的角度。默认值为 0。 |
| [blur](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/blur/) | 阴影的模糊程度。默认值为 4。 |
| [color](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/color/) | 阴影的颜色。默认值为 黑色。 |
| [distance](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/distance/) | 文本到阴影的距离。 |
| [transparency](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/transparency/) | 阴影的透明度。 |

### 另见
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
