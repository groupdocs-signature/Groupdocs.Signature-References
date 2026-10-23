---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une signature de métadonnées PDF avec un nom prédéfini et une valeur vide."
type: docs
url: /fr/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialise une signature de métadonnées PDF avec un nom prédéfini et une valeur vide.

```python
def __init__(self, name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de la signature de métadonnées PDF. |

## __init__ {#name-value}

Initialise une signature de métadonnées PDF avec des valeurs prédéfinies.

```python
def __init__(self, name, value):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de l'objet de signature de métadonnées. |
| value | `Any` | Valeur de la signature de métadonnées. |

### Exemple

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

Initialise une signature de métadonnées PDF avec des valeurs prédéfinies.

```python
def __init__(self, name, value, tag):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de l'objet de signature de métadonnées. |
| value | `Any` | Valeur de la signature de métadonnées. |
| tag | `str` | Étiquette de préfixe de la signature de métadonnées. |

### Exemple

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Créer une signature de métadonnées pour l'auteur du PDF
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Créer une signature de métadonnées pour la date de création
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Créer une signature de métadonnées pour un identifiant numérique
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Créer une signature de métadonnées pour une valeur à virgule flottante
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Voir aussi
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
