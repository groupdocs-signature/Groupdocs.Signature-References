---
title: "to_double-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert naar een float."
type: docs
url: /nl/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Converteert naar een float.

Gooit een uitzondering als de metadata-waarde niet kan worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur van [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) gebruikt.

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Converteert de metadata handtekeningwaarde naar een float.

Gebruikt de opgegeven formaatgegevensprovider om de conversie uit te voeren.

```python
def to_double(self, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** float: The metadata signature value as a float.

### Zie ook
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
