---
title: "to_decimal-metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar till Decimal."
type: docs
url: /sv/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Konverterar till Decimal.

Kastar ett undantag om metadata‑värdet inte kan konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturen från [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Konverterar metadata‑signaturvärdet till ett decimaltal.

Kastar ett undantag om metadata‑värdet inte kunde konverteras.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** float: The metadata signature value as a decimal.

### Se även
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
