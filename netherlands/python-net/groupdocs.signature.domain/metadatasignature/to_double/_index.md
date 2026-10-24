---
title: "to_double-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert de metadata handtekeningwaarde naar een float."
type: docs
url: /nl/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Converteert de metadata handtekeningwaarde naar een float.

Gooit een uitzondering als de metadatawaarde niet kan worden geconverteerd. Als de oorspronkelijke waarde een tekenreeks is, wordt de standaardcultuur van [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) gebruikt.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Converteert naar Double.

```python
def to_double(self, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** float: The metadata signature value as a float.

### Zie ook
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
