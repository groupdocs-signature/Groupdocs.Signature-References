---
title: "metodo to_decimal"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Converte il valore della firma metadata in Decimal."
type: docs
url: /it/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Converte il valore della firma metadata in Decimal.

Solleva un'eccezione se il valore dei metadati non può essere convertito. Se il valore originale è basato su stringa, le informazioni sulla cultura predefinita saranno prese da [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Converte il valore della firma metadata in un Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

**Returns:** The metadata signature value as Decimal.

### Vedi anche
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
