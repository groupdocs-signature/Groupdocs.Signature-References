---
title: "load_digital_signatures metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Tüm sistem X509 sertifika mağazalarından dijital imzaları yükle."
type: docs
url: /tr/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Tüm sistem X509 sertifika mağazalarından dijital imzaları yükle.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Bir sertifika depolama alanından dijital imzaları yükle.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Sertifikaları içeren dijital depolamanın adı. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Bir sertifika depolama alanından dijital imzaları yükle.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| store_name | `str` | Sertifikaları içeren dijital depolamanın özel adı. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Belirli bir konuma yerleştirilmiş dijital sertifika depolama alanından dijital imzaları yükle.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Sertifikaları içeren dijital depolamanın adı. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Dijital sertifika depolama konumu. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Belirli bir konuma yerleştirilmiş dijital sertifika depolama alanından dijital imzaları yükler.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| store_name | `str` | Sertifikaları içeren dijital depolamanın özel adı. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Dijital sertifika depolama konumu. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Ayrıca Bakınız
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
