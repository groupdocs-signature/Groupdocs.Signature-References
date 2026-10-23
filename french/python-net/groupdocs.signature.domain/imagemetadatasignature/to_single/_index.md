---
title: "to_single méthode"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit en float."
type: docs
url: /fr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Convertit en float.

Lance une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées depuis [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Convertit la valeur de la signature de métadonnées en float.

Lève une exception si la valeur de métadonnées n'a pas pu être convertie.

```python
def to_single(self, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** float: The metadata signature value as a float.

### Voir aussi
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
