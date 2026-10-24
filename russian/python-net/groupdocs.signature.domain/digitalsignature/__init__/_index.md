---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует цифровую подпись с параметрами по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует цифровую подпись с параметрами по умолчанию.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Инициализирует цифровую подпись с известным идентификатором подписи.

```python
def __init__(self, signature_id):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Инициализирует DigitalSignature, используя первый сертификат из указанного хранилища X509.

```python
def __init__(self, store):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | хранилище X509. |

## __init__ {#store-index}

Инициализирует DigitalSignature на основе указанного хранилища X509 и индекса сертификата.

```python
def __init__(self, store, index):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | хранилище X509. |
| index | `int` | Индекс сертификата. |

## __init__ {#certificate}

Инициализирует цифровую подпись с указанным сертификатом.

```python
def __init__(self, certificate):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | Сертификат X509. |

### См. также
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
