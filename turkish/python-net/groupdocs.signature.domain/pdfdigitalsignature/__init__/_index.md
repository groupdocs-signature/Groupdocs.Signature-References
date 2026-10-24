---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bir PDF dijital imzasını sertifika olmadan başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Bir PDF dijital imzasını sertifika olmadan başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Belirtilen X509 mağazasını kullanarak bir PDF dijital imzasını başlatır. Mağazadan ilk sertifika kullanılacaktır.

```python
def __init__(self, store):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 mağazası. |

## __init__ {#store-index}

Belirtilen X509 mağazası ve sertifika indeksi kullanılarak bir PDF dijital imzasını başlatır.

```python
def __init__(self, store, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 mağazası. |
| index | `int` | Sertifikanın dizini. |

## __init__ {#certificate}

Belirtilen X509 sertifikasıyla bir PDF dijital imzasını başlatır.

```python
def __init__(self, certificate):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 sertifikası. |

### Ayrıca Bakınız
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
