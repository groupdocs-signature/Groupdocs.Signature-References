---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует цифровую подпись PDF без сертификата."
type: docs
url: /ru/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует цифровую подпись PDF без сертификата.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Инициализирует цифровую подпись PDF, используя указанный хранилище X509. Будет использован первый сертификат из хранилища.

```python
def __init__(self, store):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | хранилище X509. |

## __init__ {#store-index}

Инициализирует цифровую подпись PDF, используя указанный хранилище X509 и индекс сертификата.

```python
def __init__(self, store, index):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | хранилище X509. |
| index | `int` | Индекс сертификата. |

## __init__ {#certificate}

Инициализирует цифровую подпись PDF с указанным сертификатом X509.

```python
def __init__(self, certificate):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | Сертификат X509. |

### См. также
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
