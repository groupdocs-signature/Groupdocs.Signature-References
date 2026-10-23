---
title: "méthode to_date_time"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit la valeur de la signature de métadonnées en `datetime.datetime`."
type: docs
url: /fr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Convertit la valeur de la signature de métadonnées en `datetime.datetime`.

Lève une exception si la valeur metadata ne peut pas être convertie. Si la valeur d'origine est basée sur une chaîne, la culture par défaut provenant de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) est utilisée.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Convertit la valeur de la signature de métadonnées en `datetime`.

Lance une exception si la valeur des métadonnées n'a pas pu être convertie.

```python
def to_date_time(self, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Voir aussi
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
