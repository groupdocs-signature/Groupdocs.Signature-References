---
title: "to_string metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata‑signaturvärdet till en sträng."
type: docs
url: /sv/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Konverterar metadata‑signaturvärdet till en sträng.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Konverterar metadata‑signaturvärdet till en sträng med det angivna formatet.

Konverterar en boolesk egenskap till "True" eller "False". Standardkulturinformationen från [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) används.

```python
def to_string(self, format):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| format | `str` | Dataformatsträng. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Konverterar till en sträng med det angivna formatet.

Konverterar en boolesk egenskap till "True" eller "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| format | `str` | Dataformatsträng. |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** str: The metadata signature value as a string.

### Se även
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
