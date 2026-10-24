---
title: "metodo to_double"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte il valore della firma metadata in un float."
type: docs
url: /it/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Converte il valore della firma metadata in un float.

Solleva un'eccezione se il valore dei metadati non può essere convertito. Se il valore originale è basato su stringa, la cultura predefinita da [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) viene utilizzata.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Converte in Double.

```python
def to_double(self, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** float: The metadata signature value as a float.

### Vedi anche
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
