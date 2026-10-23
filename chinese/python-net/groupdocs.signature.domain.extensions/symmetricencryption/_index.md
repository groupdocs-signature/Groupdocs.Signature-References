---
title: "SymmetricEncryption 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "实现使用单一密钥和密码短语（盐）的数据加密标准对称算法。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/symmetricencryption/
is_root: false
weight: 360
---


## SymmetricEncryption class

实现使用单一密钥和密码短语（盐）的数据加密标准对称算法。

SymmetricEncryption 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/#algorithm_type-key-salt) | 使用指定的参数初始化对称加密算法。 |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/#algorithm_type-key) | 使用默认口令初始化对称加密算法。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [decode](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/decode/#source) | 使用配置的算法、密钥和盐解密字符串。 |
| [decode_file](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/decode_file/) |  |
| [decode_string](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/decode_string/) |  |
| [encode](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/encode/#source) | 根据提供的算法类型、密钥和盐参数加密字符串。 |
| [encode_file](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/encode_file/) |  |
| [encode_string](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/encode_string/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [algorithm_type](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/algorithm_type/) | 对称算法的类型。 |
| [key](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/key/) | 加密算法的密钥。 |
| [salt](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/salt/) | 加密算法的口令。 |

### 另见
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
