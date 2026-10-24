---
title: "metodo to_double"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte in un float."
type: docs
url: /it/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Converte in un float.

Genera un'eccezione se il valore metadata non può essere convertito. Se il valore originale è basato su stringa, viene utilizzata la cultura predefinita da [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Converte il valore della firma metadata in un float.

Utilizza il provider di formato dati specificato per eseguire la conversione.

```python
def to_double(self, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** float: The metadata signature value as a float.

### Vedi anche
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
