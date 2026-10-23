---
title: "custom_sign_hash 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用自定义签名实现对给定的哈希进行签名。"
type: docs
url: /zh/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

使用自定义签名实现对给定的哈希进行签名。

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signable_hash | `list[int]` | 要签名的哈希值。 |
| hash_algorithm | `HashAlgorithm` | 用于生成哈希的哈希算法。 |
| signature_context | `SignatureContext` | 提供额外签名相关选项的上下文。 |

**Returns:** bytes: The signed hash as bytes.

### 另见
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
