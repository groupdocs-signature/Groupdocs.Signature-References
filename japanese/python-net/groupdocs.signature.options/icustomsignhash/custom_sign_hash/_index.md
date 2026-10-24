---
title: "custom_sign_hash メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "カスタム署名実装を使用して指定されたハッシュに署名します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

カスタム署名実装を使用して指定されたハッシュに署名します。

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signable_hash | `list[int]` | 署名対象のハッシュ値。 |
| hash_algorithm | `HashAlgorithm` | ハッシュ生成に使用されるハッシュアルゴリズム。 |
| signature_context | `SignatureContext` | 追加の署名関連オプションを提供するコンテキスト。 |

**Returns:** bytes: The signed hash as bytes.

### 関連項目
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
