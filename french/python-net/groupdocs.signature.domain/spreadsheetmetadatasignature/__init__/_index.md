---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise Spreadsheet Metadata Signature avec un nom prédéfini et une valeur vide."
type: docs
url: /fr/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialise Spreadsheet Metadata Signature avec un nom prédéfini et une valeur vide.

```python
def __init__(self, name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de la signature de métadonnées de feuille de calcul. |

## __init__ {#name-value}

Initialise une Spreadsheet Metadata Signature avec des valeurs prédéfinies.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Créer des signatures de métadonnées pour une feuille de calcul
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Voir aussi
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
