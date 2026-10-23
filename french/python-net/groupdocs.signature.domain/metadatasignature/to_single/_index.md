---
title: "to_single méthode"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit la valeur de la signature de métadonnées en float."
type: docs
url: /fr/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Convertit la valeur de la signature de métadonnées en float.

Lève une exception si la valeur metadata ne peut pas être convertie. Si la valeur d'origine est basée sur une chaîne, la culture par défaut provenant de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) est utilisée.

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Convertit en float.

```python
def to_single(self, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** float: The Metadata Signature value as float.

### Voir aussi
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
