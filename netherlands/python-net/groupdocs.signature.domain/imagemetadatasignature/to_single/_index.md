---
title: "to_single methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert naar float."
type: docs
url: /nl/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Converteert naar float.

Gooit een uitzondering als de Metadata‑waarde niet kon worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur‑eigenschapsinformatie gebruikt van [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Converteert de metadata handtekeningwaarde naar een float.

Werpt een uitzondering als de metadatawaarde niet kon worden geconverteerd.

```python
def to_single(self, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** float: The metadata signature value as a float.

### Zie ook
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
