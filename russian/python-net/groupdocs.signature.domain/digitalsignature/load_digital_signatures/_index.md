---
title: "метод load_digital_signatures"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Загружает цифровые подписи из всех системных хранилищ сертификатов X509."
type: docs
url: /ru/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Загружает цифровые подписи из всех системных хранилищ сертификатов X509.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Загружает цифровые подписи из хранилища сертификатов.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Имя цифрового хранилища, содержащего сертификаты. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Загружает цифровые подписи из хранилища сертификатов.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| store_name | `str` | Пользовательское имя цифрового хранилища, содержащего сертификаты. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Загружает цифровые подписи из хранилища цифровых сертификатов, расположенного в определённом месте.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Имя цифрового хранилища, содержащего сертификаты. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Расположение цифрового хранилища сертификатов. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Загружает цифровые подписи из хранилища цифровых сертификатов, размещённого в определённом месте.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| store_name | `str` | Пользовательское имя цифрового хранилища, содержащего сертификаты. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Расположение цифрового хранилища сертификатов. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### См. также
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
