---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine digitale Signatur mit Standardparametern."
type: docs
url: /de/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine digitale Signatur mit Standardparametern.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Initialisiert eine digitale Signatur mit einer bekannten Signatur-ID.

```python
def __init__(self, signature_id):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Initialisiert ein DigitalSignature unter Verwendung des ersten Zertifikats aus dem angegebenen X509-Store.

```python
def __init__(self, store):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509‑Speicher. |

## __init__ {#store-index}

Initialisiert ein DigitalSignature basierend auf dem angegebenen X509-Store und dem Zertifikatsindex.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509‑Speicher. |
| index | `int` | Index des Zertifikats. |

## __init__ {#certificate}

Initialisiert eine digitale Signatur mit dem angegebenen Zertifikat.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509‑Zertifikat. |

### Siehe auch
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
