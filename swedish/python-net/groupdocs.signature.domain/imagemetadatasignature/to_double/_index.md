---
title: "to_double metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar till ett flyttal."
type: docs
url: /sv/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Konverterar till ett flyttal.

Kastar ett undantag om metadata-värdet inte kan konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturen från [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Konverterar metadata-signaturens värde till en float.

Använder den angivna formatdataleverantören för att utföra konverteringen.

```python
def to_double(self, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** float: The metadata signature value as a float.

### Se även
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
