---
title: "to_single-metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar till float."
type: docs
url: /sv/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Konverterar till float.

Kastar ett undantag om Metadata‑värdet inte kunde konverteras. Om det ursprungliga värdet är strängbaserat används standardkultur‑egenskapsinformationen från [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Konverterar metadata-signaturens värde till en float.

Kastar ett undantag om metadata‑värdet inte kunde konverteras.

```python
def to_single(self, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** float: The metadata signature value as a float.

### Se även
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
