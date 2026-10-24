---
title: "to_decimal-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert naar Decimal."
type: docs
url: /nl/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Converteert naar Decimal.

Gooit een uitzondering als de metadatawaarde niet kan worden geconverteerd. Als de oorspronkelijke waarde een tekenreeks is, wordt de standaardcultuur van [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) gebruikt.

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Converteert de metadata‑handtekeningwaarde naar een decimaal.

Werpt een uitzondering als de metadatawaarde niet kon worden geconverteerd.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** float: The metadata signature value as a decimal.

### Zie ook
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
