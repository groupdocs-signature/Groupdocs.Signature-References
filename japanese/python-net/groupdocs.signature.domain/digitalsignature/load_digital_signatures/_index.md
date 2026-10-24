---
title: "load_digital_signatures メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "すべてのシステム X509 証明書ストアからデジタル署名をロードします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

すべてのシステム X509 証明書ストアからデジタル署名をロードします。

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

証明書ストレージからデジタル署名をロードします。

```python
def load_digital_signatures(cls, store_name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | 証明書を含むデジタルストレージの名前。 |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

証明書ストレージからデジタル署名をロードします。

```python
def load_digital_signatures(cls, store_name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| store_name | `str` | 証明書を含むデジタルストレージのカスタム名。 |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

特定の場所に配置されたデジタル証明書ストレージからデジタル署名をロードします。

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | 証明書を含むデジタルストレージの名前。 |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | デジタル証明書ストレージの場所。 |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

特定の場所に配置されたデジタル証明書ストレージからデジタル署名をロードします。

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| store_name | `str` | 証明書を含むデジタルストレージのカスタム名。 |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | デジタル証明書ストレージの場所。 |

**Returns:** list[DigitalSignature]: List of digital signatures.

### 関連項目
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
