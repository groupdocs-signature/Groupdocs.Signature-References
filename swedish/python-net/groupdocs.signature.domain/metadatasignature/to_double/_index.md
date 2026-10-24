---
title: "to_double metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata-signaturens värde till en float."
type: docs
url: /sv/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Konverterar metadata-signaturens värde till en float.

Kastar ett undantag om metadata‑värdet inte kan konverteras. Om det ursprungliga värdet är strängbaserat används standardkulturen från [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Konverterar till Double.

```python
def to_double(self, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** float: The metadata signature value as a float.

### Se även
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
