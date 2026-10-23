---
title: "méthode to_string"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit la valeur de la signature de métadonnées en chaîne."
type: docs
url: /fr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Convertit la valeur de la signature de métadonnées en chaîne.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Convertit la valeur de la signature de métadonnées en chaîne en utilisant le format spécifié.

Convertit une propriété booléenne en "True" ou "False". Les informations de culture par défaut provenant de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) sont utilisées.

```python
def to_string(self, format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| format | `str` | Chaîne de format de données. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Convertit en chaîne avec le format spécifié.

Convertit une propriété booléenne en "True" ou "False".

```python
def to_string(self, format, provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| format | `str` | Chaîne de format de données. |
| provider | `System.IFormatProvider` | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

**Returns:** str: The metadata signature value as a string.

### Voir aussi
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
