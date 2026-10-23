---
title: "méthode to_double"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit en flottant."
type: docs
url: /fr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Convertit en flottant.

Lève une exception si la valeur metadata ne peut pas être convertie. Si la valeur d'origine est basée sur une chaîne, la culture par défaut provenant de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) est utilisée.

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Convertit la valeur de la signature de métadonnées en float.

Utilise le fournisseur de format de données spécifié pour effectuer la conversion.

```python
def to_double(self, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** float: The metadata signature value as a float.

### Voir aussi
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
