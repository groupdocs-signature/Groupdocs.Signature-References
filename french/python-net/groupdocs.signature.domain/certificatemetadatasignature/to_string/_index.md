---
title: "méthode to_string"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Convertit la signature de métadonnées en chaîne en utilisant la méthode ToString remplacée."
type: docs
url: /fr/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Convertit la signature de métadonnées en chaîne en utilisant la méthode ToString remplacée.

Convertit une propriété booléenne en "True" ou "False". Pour les autres types de données, le fournisseur de format de données par défaut est utilisé.

```python
def to_string(self):
    ...
```

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

**Returns:** The metadata signature value as a string.

### Voir aussi
* class [`CertificateMetadataSignature`](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/)
