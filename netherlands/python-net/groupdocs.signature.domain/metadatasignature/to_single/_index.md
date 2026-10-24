---
title: "to_single methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert de metadata handtekeningwaarde naar een float."
type: docs
url: /nl/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Converteert de metadata handtekeningwaarde naar een float.

Gooit een uitzondering als de metadata-waarde niet kan worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur van [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) gebruikt.

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Converteert naar float.

```python
def to_single(self, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** float: The Metadata Signature value as float.

### Zie ook
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
