---
title: "load_digital_signatures 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "从所有系统 X509 证书存储加载数字签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

从所有系统 X509 证书存储加载数字签名。

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

从证书存储加载数字签名。

```python
def load_digital_signatures(cls, store_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | 包含证书的数字存储的名称。 |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

从证书存储加载数字签名。

```python
def load_digital_signatures(cls, store_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| store_name | `str` | 包含证书的数字存储的自定义名称。 |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

从放置在特定位置的数字证书存储加载数字签名。

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | 包含证书的数字存储的名称。 |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | 数字证书存储的位置。 |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

从放置在特定位置的数字证书存储加载数字签名。

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| store_name | `str` | 包含证书的数字存储的自定义名称。 |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | 数字证书存储的位置。 |

**Returns:** list[DigitalSignature]: List of digital signatures.

### 另见
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
