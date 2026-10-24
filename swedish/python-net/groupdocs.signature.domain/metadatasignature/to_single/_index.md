---
title: "to_single-metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata-signaturens värde till en float."
type: docs
url: /sv/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Konverterar metadata-signaturens värde till en float.

Kastar ett undantag om metadata-värdet inte kan konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturen från [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Konverterar till float.

```python
def to_single(self, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** float: The Metadata Signature value as float.

### Se även
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
