---
title: "to_date_time-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert de metadata-handtekeningwaarde naar een datetime.datetime."
type: docs
url: /nl/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Converteert de metadata‑handtekeningwaarde naar een `datetime.datetime`.

Gooit een uitzondering als de metadata-waarde niet kan worden geconverteerd. Als de oorspronkelijke waarde op een string is gebaseerd, wordt de standaardcultuur van [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) gebruikt.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Converteert de metadata‑handtekeningwaarde naar een `datetime`.

Gooit een uitzondering als de metadatawaarde niet kon worden geconverteerd.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Zie ook
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
