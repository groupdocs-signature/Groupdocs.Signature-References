---
title: "to_string metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata-signaturen till en sträng."
type: docs
url: /sv/python-net/groupdocs.signature.domain/presentationmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Konverterar metadata-signaturen till en sträng.

Konverterar en boolesk egenskap till "True" eller "False". För andra datatyper används standarddatatypformatleverantören.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Konverterar till sträng med angivet format.

Konverterar en boolesk egenskap till "True" eller "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| format | `str` | Dataformatsträng. |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** str: The metadata signature value as string.

### Se även
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
