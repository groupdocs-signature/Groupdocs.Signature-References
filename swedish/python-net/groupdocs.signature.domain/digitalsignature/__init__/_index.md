---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en digital signatur med standardparametrar."
type: docs
url: /sv/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en digital signatur med standardparametrar.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Initierar en digital signatur med en känd signaturidentifierare.

```python
def __init__(self, signature_id):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Initierar en DigitalSignature med det första certifikatet från den angivna X509-butiken.

```python
def __init__(self, store):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509‑lagring. |

## __init__ {#store-index}

Initierar en DigitalSignature baserat på den angivna X509-butiken och certifikatindexet.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509‑lagring. |
| index | `int` | Index för certifikatet. |

## __init__ {#certificate}

Initierar en digital signatur med det angivna certifikatet.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509‑certifikat. |

### Se även
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
