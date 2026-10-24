---
title: "metodo to_string"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte la firma metadata in una stringa."
type: docs
url: /it/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Converte la firma metadata in una stringa.

Converte una proprietà booleana in "True" o "False". Per altri tipi di dati viene utilizzato il provider di formato dati predefinito.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converte la firma di metadati in una stringa con il formato specificato.

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
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
