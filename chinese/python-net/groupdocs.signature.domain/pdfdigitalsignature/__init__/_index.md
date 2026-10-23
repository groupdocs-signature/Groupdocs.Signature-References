---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "在没有证书的情况下初始化 PDF 数字签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

在没有证书的情况下初始化 PDF 数字签名。

```python
def __init__(self):
    ...
```

## __init__ {#store}

使用指定的 X509 存储初始化 PDF 数字签名。将使用该存储中的第一张证书。

```python
def __init__(self, store):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 存储。 |

## __init__ {#store-index}

使用指定的 X509 存储和证书索引初始化 PDF 数字签名。

```python
def __init__(self, store, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 存储。 |
| index | `int` | 证书索引。 |

## __init__ {#certificate}

使用指定的 X509 证书初始化 PDF 数字签名。

```python
def __init__(self, certificate):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 证书。 |

### 另见
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
