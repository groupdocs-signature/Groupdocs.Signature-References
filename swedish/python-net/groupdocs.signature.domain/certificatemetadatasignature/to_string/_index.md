---
title: "to_string metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata‑signaturen till en sträng med den överskuggade ToString‑metoden."
type: docs
url: /sv/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Konverterar metadata‑signaturen till en sträng med den överskuggade ToString‑metoden.

Konverterar en boolesk egenskap till "True" eller "False". För andra datatyper används standarddatatypformatleverantören.

```python
def to_string(self):
    ...
```

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

**Returns:** The metadata signature value as a string.

### Se även
* class [`CertificateMetadataSignature`](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/)
