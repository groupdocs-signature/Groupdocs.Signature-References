---
title: "to_decimal-metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata-signaturens värde till Decimal."
type: docs
url: /sv/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Konverterar metadata-signaturens värde till Decimal.

Kastar ett undantag om metadata-värdet inte kunde konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturens egenskapsinformation från [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Konverterar metadata-signaturens värde till en Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** The metadata signature value as Decimal.

### Se även
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
