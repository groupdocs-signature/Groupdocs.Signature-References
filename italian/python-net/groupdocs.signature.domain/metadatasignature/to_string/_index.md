---
title: "metodo to_string"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte la firma metadata in una stringa."
type: docs
url: /it/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

Converte la firma metadata in una stringa.

Converte una proprietà booleana in "True" o "False". Per altri tipi di dati verrà utilizzato il provider di formattazione dati predefinito.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

Converte la firma metadata in una stringa utilizzando il formato specificato.

Converte una proprietà booleana in "True" o "False". Le informazioni sulla cultura predefinita saranno prese dalle proprietà di SignatureSettings [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| format | `str` | Stringa di formattazione dati. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converte in stringa con formato specificato.

Converte una proprietà booleana in "True" o "False".

```python
def to_string(self, format, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| format | `str` | Stringa di formattazione dati. |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** The metadata signature value as a string.

### Vedi anche
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
