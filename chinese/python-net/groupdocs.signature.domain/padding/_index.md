---
title: "Padding 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示与元素关联的填充或边距信息。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

表示与元素关联的填充或边距信息。

Padding 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | 使用零值初始化 Padding 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | 使用提供的填充尺寸为所有边缘初始化 Padding 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | 使用提供的填充尺寸初始化 Padding 类的新实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | 获取此对象的副本。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | 所有边缘的填充值。 |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | 底部边缘的填充值。 |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | 左右边缘的组合填充值。 |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | 左侧边缘的填充值。 |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | 右侧边缘的填充值。 |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | 顶部边缘的填充值。 |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | 上下边缘的组合填充值。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | 提供一个没有填充的 Padding 对象。 |

### 示例

```python
from groupdocs.signature.domain import Padding

# 所有侧面统一 5 单位的填充
uniform = Padding(5)

# 右侧和底部的特定填充
custom = Padding(right=40, bottom=60)
```

### Guides
使用 `Padding` 的任务指南：

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
