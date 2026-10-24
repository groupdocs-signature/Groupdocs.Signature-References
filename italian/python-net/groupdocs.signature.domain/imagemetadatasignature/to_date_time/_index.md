---
title: "metodo to_date_time"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte il valore della firma di metadati in un datetime.datetime."
type: docs
url: /it/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Converte il valore della firma di metadati in un `datetime.datetime`.

Genera un'eccezione se il valore metadata non può essere convertito. Se il valore originale è basato su stringa, viene utilizzata la cultura predefinita da [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Converte il valore della firma di metadati in un `datetime`.

Lancia un'eccezione se il valore dei metadati non può essere convertito.

```python
def to_date_time(self, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Vedi anche
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
