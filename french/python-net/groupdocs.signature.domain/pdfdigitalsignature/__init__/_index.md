---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une signature numérique PDF sans certificat."
type: docs
url: /fr/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une signature numérique PDF sans certificat.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Initialise une signature numérique PDF en utilisant le magasin X509 spécifié. Le premier certificat du magasin sera utilisé.

```python
def __init__(self, store):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | magasin X509. |

## __init__ {#store-index}

Initialise une signature numérique PDF en utilisant le magasin X509 spécifié et l'index du certificat.

```python
def __init__(self, store, index):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | magasin X509. |
| index | `int` | Index du certificat. |

## __init__ {#certificate}

Initialise une signature numérique PDF avec le certificat X509 spécifié.

```python
def __init__(self, certificate):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | certificat X509. |

### Voir aussi
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
