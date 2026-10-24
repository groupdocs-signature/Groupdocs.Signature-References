---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定されたパラメーターで対称アルゴリズムを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

指定されたパラメーターで対称アルゴリズムを初期化します。

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | 対称アルゴリズムのタイプを指定 |
| key | `str` | 暗号化キー |
| salt | `str` | 暗号化用パスフレーズ |

## __init__ {#algorithm_type-key}

パラメーターとデフォルトのパスフレーズで対称アルゴリズムを初期化します。

```python
def __init__(self, algorithm_type, key):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | 暗号化アルゴリズムのタイプ |
| key | `str` | 暗号化キー |

### 関連項目
* class [`SymmetricEncryptionAttribute`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/)
