---
title: "méthode to_double"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit la valeur de la signature de métadonnées en float."
type: docs
url: /fr/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Convertit la valeur de la signature de métadonnées en float.

Lève une exception si la valeur des métadonnées ne peut pas être convertie. Si la valeur d'origine est basée sur une chaîne, la culture par défaut provenant de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) est utilisée.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Convertit en Double.

```python
def to_double(self, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** float: The metadata signature value as a float.

### Voir aussi
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
