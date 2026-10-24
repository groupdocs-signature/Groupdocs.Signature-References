---
title: "load_digital_signatures methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Laadt digitale handtekeningen uit alle systeem X509-certificaatopslagplaatsen."
type: docs
url: /nl/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Laadt digitale handtekeningen uit alle systeem X509-certificaatopslagplaatsen.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Laadt digitale handtekeningen uit een certificaatopslag.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Naam van een digitale opslag die certificaten bevat. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Laadt digitale handtekeningen uit een certificaatopslag.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| store_name | `str` | Aangepaste naam van een digitale opslag die certificaten bevat. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Laadt digitale handtekeningen uit een digitale certificaatopslag op een specifieke locatie.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Naam van een digitale opslag die certificaten bevat. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Locatie van een digitale certificaatopslag. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Laadt digitale handtekeningen uit een digitale certificaatopslag geplaatst op een specifieke locatie.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| store_name | `str` | Aangepaste naam van een digitale opslag die certificaten bevat. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Locatie van een digitale certificaatopslag. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Zie ook
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
