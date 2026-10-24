---
title: "metodo to_string"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte il valore della firma di metadati in una stringa."
type: docs
url: /it/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Converte il valore della firma di metadati in una stringa.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Converte il valore della firma di metadati in una stringa usando il formato specificato.

Converte una proprietà booleana in "True" o "False". Viene utilizzata l'informazione di cultura predefinita da [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| format | `str` | Stringa di formattazione dati. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converte in una stringa con il formato specificato.

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
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
