---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une signature numérique avec les paramètres par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une signature numérique avec les paramètres par défaut.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Initialise une signature numérique avec un identifiant de signature connu.

```python
def __init__(self, signature_id):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Initialise un DigitalSignature en utilisant le premier certificat du magasin X509 spécifié.

```python
def __init__(self, store):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | magasin X509. |

## __init__ {#store-index}

Initialise un DigitalSignature basé sur le magasin X509 spécifié et l'index du certificat.

```python
def __init__(self, store, index):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | magasin X509. |
| index | `int` | Index du certificat. |

## __init__ {#certificate}

Initialise une signature numérique avec le certificat spécifié.

```python
def __init__(self, certificate):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | certificat X509. |

### Voir aussi
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
