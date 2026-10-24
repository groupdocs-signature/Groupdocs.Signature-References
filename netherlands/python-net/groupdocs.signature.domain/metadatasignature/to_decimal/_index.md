---
title: "to_decimal-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert de metadata handtekeningwaarde naar Decimal."
type: docs
url: /nl/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Converteert de metadata handtekeningwaarde naar Decimal.

Gooit een uitzondering als de metadatawaarde niet kon worden geconverteerd. Als de oorspronkelijke waarde een tekenreeks is, wordt de informatie over de standaardcultuur gebruikt uit [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Converteert de metadata handtekeningwaarde naar Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** The metadata signature value as Decimal.

### Zie ook
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
