---
title: "méthode to_decimal"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit en Decimal."
type: docs
url: /fr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Convertit en Decimal.

Lève une exception si la valeur des métadonnées ne peut pas être convertie. Si la valeur d'origine est basée sur une chaîne, la culture par défaut provenant de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) est utilisée.

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Convertit la valeur de la signature de métadonnées en décimal.

Lève une exception si la valeur de métadonnées n'a pas pu être convertie.

```python
def to_decimal(self, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** float: The metadata signature value as a decimal.

### Voir aussi
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
