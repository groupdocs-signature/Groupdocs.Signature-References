---
title: "méthode to_date_time"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit la valeur de la signature de métadonnées en datetime."
type: docs
url: /fr/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Convertit la valeur de la signature de métadonnées en datetime.

Si la valeur des métadonnées ne peut pas être convertie, une exception est levée. Lorsque la valeur d'origine est basée sur une chaîne, la culture par défaut provenant de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) est utilisée pour la conversion.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Convertit la valeur de la signature de métadonnées en datetime.

```python
def to_date_time(self, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Lance une exception si la valeur des métadonnées n'a pas pu être convertie.

### Voir aussi
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
