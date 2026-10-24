---
title: "to_single metodo"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte in float."
type: docs
url: /it/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Converte in float.

Genera un'eccezione se il valore dei Metadati non può essere convertito. Se il valore originale è basato su stringa, verrà utilizzata l'informazione della proprietà cultura predefinita da [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Converte il valore della firma metadata in un float.

Genera un'eccezione se il valore dei metadati non può essere convertito.

```python
def to_single(self, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** float: The metadata signature value as a float.

### Vedi anche
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
