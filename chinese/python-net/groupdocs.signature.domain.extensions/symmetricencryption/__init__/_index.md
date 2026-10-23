---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用指定的参数初始化对称加密算法。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

使用指定的参数初始化对称加密算法。

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | 指定对称算法类型 |
| key | `str` | 加密密钥 |
| salt | `str` | 用于加密的密码短语 |

## __init__ {#algorithm_type-key}

使用默认口令初始化对称加密算法。

```python
def __init__(self, algorithm_type, key):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | 指定对称算法类型。 |
| key | `str` | 加密密钥。 |

### 另见
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
