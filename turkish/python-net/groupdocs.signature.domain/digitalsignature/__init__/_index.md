---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Varsayılan parametrelerle bir dijital imza başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Varsayılan parametrelerle bir dijital imza başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Bilinen bir imza tanımlayıcısı ile bir dijital imza başlatır.

```python
def __init__(self, signature_id):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Belirtilen X509 mağazasından ilk sertifikayı kullanarak bir DigitalSignature başlatır.

```python
def __init__(self, store):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 mağazası. |

## __init__ {#store-index}

Belirtilen X509 mağazası ve sertifika indeksi temelinde bir DigitalSignature başlatır.

```python
def __init__(self, store, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509 mağazası. |
| index | `int` | Sertifikanın dizini. |

## __init__ {#certificate}

Belirtilen sertifika ile bir dijital imza başlatır.

```python
def __init__(self, certificate):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509 sertifikası. |

### Ayrıca Bakınız
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
