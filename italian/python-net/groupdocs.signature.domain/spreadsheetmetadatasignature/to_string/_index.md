---
title: "metodo to_string"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte il valore della firma dei metadati in una stringa usando il metodo ToString sovrascritto."
type: docs
url: /it/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Converte il valore della firma dei metadati in una stringa usando il metodo `ToString` sovrascritto.

Converte una proprietà booleana in `True` o `False`. Per altri tipi di dati, viene utilizzato il provider di formato dati predefinito.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converte la firma metadata in una stringa utilizzando il formato specificato.

Converte una proprietà booleana in "True" o "False".

```python
def to_string(self, format, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| format | `str` | Stringa di formattazione dati. |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** str: The metadata signature value as a string.

### Vedi anche
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
