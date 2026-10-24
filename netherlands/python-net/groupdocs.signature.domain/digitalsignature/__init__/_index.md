---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een digitale handtekening met standaardparameters."
type: docs
url: /nl/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een digitale handtekening met standaardparameters.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Initialiseert een digitale handtekening met een bekende handtekeningidentificatie.

```python
def __init__(self, signature_id):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Initialiseert een DigitalSignature met het eerste certificaat uit de opgegeven X509-opslag.

```python
def __init__(self, store):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509-opslag. |

## __init__ {#store-index}

Initialiseert een DigitalSignature op basis van de opgegeven X509-opslag en certificaatindex.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509-opslag. |
| index | `int` | Index van het certificaat. |

## __init__ {#certificate}

Initialiseert een digitale handtekening met het opgegeven certificaat.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509-certificaat. |

### Zie ook
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
