---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een digitale PDF-handtekening zonder certificaat."
type: docs
url: /nl/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een digitale PDF-handtekening zonder certificaat.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Initialiseert een digitale PDF-handtekening met de opgegeven X509-winkel. Het eerste certificaat uit de winkel wordt gebruikt.

```python
def __init__(self, store):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509-opslag. |

## __init__ {#store-index}

Initialiseert een digitale PDF-handtekening met de opgegeven X509-winkel en certificaatindex.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | X509-opslag. |
| index | `int` | Index van certificaat. |

## __init__ {#certificate}

Initialiseert een digitale PDF-handtekening met het opgegeven X509-certificaat.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | X509-certificaat. |

### Zie ook
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
