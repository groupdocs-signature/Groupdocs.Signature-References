---
title: "load_digital_signatures Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Lädt digitale Signaturen aus allen System-X509-Zertifikatsstores."
type: docs
url: /de/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Lädt digitale Signaturen aus allen System-X509-Zertifikatsstores.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Lädt digitale Signaturen aus einem Zertifikatspeicher.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Name eines digitalen Speichers, der Zertifikate enthält. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Lädt digitale Signaturen aus einem Zertifikatspeicher.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| store_name | `str` | Benutzerdefinierter Name eines digitalen Speichers, der Zertifikate enthält. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Lädt digitale Signaturen aus einem digitalen Zertifikatspeicher, der an einem bestimmten Ort abgelegt ist.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Name eines digitalen Speichers, der Zertifikate enthält. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Speicherort eines digitalen Zertifikatsspeichers. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Lädt digitale Signaturen aus einem digitalen Zertifikatspeicher, der an einem bestimmten Ort abgelegt ist.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| store_name | `str` | Benutzerdefinierter Name eines digitalen Speichers, der Zertifikate enthält. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Speicherort eines digitalen Zertifikatsspeichers. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Siehe auch
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
