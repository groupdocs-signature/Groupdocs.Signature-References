---
title: "to_date_time metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata‑signaturvärdet till ett datetime.datetime."
type: docs
url: /sv/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Konverterar metadata‑signaturvärdet till en `datetime.datetime`.

Kastar ett undantag om metadata-värdet inte kan konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturen från [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Konverterar metadata‑signaturvärdet till en `datetime`.

Kastar ett undantag om metadata‑värdet inte kunde konverteras.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Se även
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
