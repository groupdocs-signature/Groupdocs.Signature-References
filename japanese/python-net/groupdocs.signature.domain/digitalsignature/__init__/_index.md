---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルトパラメータでデジタル署名を初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

デフォルトパラメータでデジタル署名を初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

既知の署名識別子でデジタル署名を初期化します。

```python
def __init__(self, signature_id):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

指定された X509 ストアの最初の証明書を使用して DigitalSignature を初期化します。

```python
def __init__(self, store):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 ストア。 |

## __init__ {#store-index}

指定された X509 ストアと証明書インデックスに基づいて DigitalSignature を初期化します。

```python
def __init__(self, store, index):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 ストア。 |
| index | `int` | 証明書のインデックス。 |

## __init__ {#certificate}

指定された証明書でデジタル署名を初期化します。

```python
def __init__(self, certificate):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 証明書。 |

### 関連項目
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
