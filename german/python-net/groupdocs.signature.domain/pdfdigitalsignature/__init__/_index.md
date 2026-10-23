---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine PDF-Digitale Signatur ohne Zertifikat."
type: docs
url: /de/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine PDF-Digitale Signatur ohne Zertifikat.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Initialisiert eine PDF-Digitale Signatur unter Verwendung des angegebenen X509-Speichers. Das erste Zertifikat aus dem Speicher wird verwendet.

```python
def __init__(self, store):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509‑Speicher. |

## __init__ {#store-index}

Initialisiert eine PDF-Digitale Signatur unter Verwendung des angegebenen X509-Speichers und des Zertifikatsindex.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509‑Speicher. |
| index | `int` | Index des Zertifikats. |

## __init__ {#certificate}

Initialisiert eine PDF-Digitale Signatur mit dem angegebenen X509-Zertifikat.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509‑Zertifikat. |

### Siehe auch
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
