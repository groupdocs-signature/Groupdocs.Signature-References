---
title: "metodo to_decimal"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte in Decimal."
type: docs
url: /it/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Converte in Decimal.

Solleva un'eccezione se il valore dei metadati non può essere convertito. Se il valore originale è basato su stringa, la cultura predefinita da [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) viene utilizzata.

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Converte il valore della firma di metadati in un decimale.

Genera un'eccezione se il valore dei metadati non può essere convertito.

```python
def to_decimal(self, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** float: The metadata signature value as a decimal.

### Vedi anche
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
