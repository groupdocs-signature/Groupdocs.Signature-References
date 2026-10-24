---
title: "metodo to_date_time"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte il valore della firma metadata in un datetime."
type: docs
url: /it/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Converte il valore della firma metadata in un datetime.

Se il valore dei metadati non può essere convertito, viene sollevata un'eccezione. Quando il valore originale è basato su stringa, la cultura predefinita da [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) viene utilizzata per la conversione.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Converte il valore della firma metadata in un datetime.

```python
def to_date_time(self, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Lancia un'eccezione se il valore dei metadati non può essere convertito.

### Vedi anche
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
