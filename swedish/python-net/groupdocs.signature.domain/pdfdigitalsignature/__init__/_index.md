---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en PDF‑digital signatur utan ett certifikat."
type: docs
url: /sv/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en PDF‑digital signatur utan ett certifikat.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Initierar en PDF‑digital signatur med den angivna X509‑lagringen. Det första certifikatet från lagringen kommer att användas.

```python
def __init__(self, store):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509‑lagring. |

## __init__ {#store-index}

Initierar en PDF-digital signatur med den angivna X509-lagret och certifikatindexet.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509‑lagring. |
| index | `int` | Index för certifikat. |

## __init__ {#certificate}

Initierar en PDF-digital signatur med det angivna X509-certifikatet.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509‑certifikat. |

### Se även
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
