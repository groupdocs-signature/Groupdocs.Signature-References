---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认参数初始化数字签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

使用默认参数初始化数字签名。

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

使用已知的签名标识符初始化数字签名。

```python
def __init__(self, signature_id):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

使用指定 X509 存储中的第一个证书初始化 DigitalSignature。

```python
def __init__(self, store):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 存储。 |

## __init__ {#store-index}

根据指定的 X509 存储和证书索引初始化 DigitalSignature。

```python
def __init__(self, store, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 存储。 |
| index | `int` | 证书的索引。 |

## __init__ {#certificate}

使用指定的证书初始化数字签名。

```python
def __init__(self, certificate):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 证书。 |

### 另见
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
