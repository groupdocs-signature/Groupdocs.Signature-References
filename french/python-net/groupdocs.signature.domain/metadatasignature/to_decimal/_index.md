---
title: "méthode to_decimal"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit la valeur de la signature de métadonnées en Decimal."
type: docs
url: /fr/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Convertit la valeur de la signature de métadonnées en Decimal.

Lève une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de culture par défaut seront utilisées à partir de [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Convertit la valeur de la signature de métadonnées en Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** The metadata signature value as Decimal.

### Voir aussi
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
