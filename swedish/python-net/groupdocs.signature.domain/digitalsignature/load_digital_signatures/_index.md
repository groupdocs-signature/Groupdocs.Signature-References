---
title: "load_digital_signatures-metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Läs in digitala signaturer från alla systemets X509-certifikatbutiker."
type: docs
url: /sv/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Läs in digitala signaturer från alla systemets X509-certifikatbutiker.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Läs in digitala signaturer från ett certifikatlagringsutrymme.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Namn på ett digitalt lagringsutrymme som innehåller certifikat. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Läs in digitala signaturer från ett certifikatlagringsutrymme.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| store_name | `str` | Anpassat namn på ett digitalt lagringsutrymme som innehåller certifikat. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Läs in digitala signaturer från ett digitalt certifikatlagringsutrymme placerat på en specifik plats.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Namn på ett digitalt lagringsutrymme som innehåller certifikat. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Plats för ett digitalt certifikatlagringsutrymme. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Läser in digitala signaturer från ett digitalt certifikatlagringsutrymme placerat på en specifik plats.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| store_name | `str` | Anpassat namn på ett digitalt lagringsutrymme som innehåller certifikat. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Plats för ett digitalt certifikatlagringsutrymme. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Se även
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
