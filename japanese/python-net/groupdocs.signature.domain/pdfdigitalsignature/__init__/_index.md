---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "証明書なしで PDF デジタル署名を初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

証明書なしで PDF デジタル署名を初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#store}

指定された X509 ストアを使用して PDF デジタル署名を初期化します。ストアから最初の証明書が使用されます。

```python
def __init__(self, store):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 ストア。 |

## __init__ {#store-index}

指定された X509 ストアと証明書インデックスを使用して PDF デジタル署名を初期化します。

```python
def __init__(self, store, index):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 ストア。 |
| index | `int` | 証明書のインデックス。 |

## __init__ {#certificate}

指定された X509 証明書で PDF デジタル署名を初期化します。

```python
def __init__(self, certificate):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 証明書。 |

### 関連項目
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
