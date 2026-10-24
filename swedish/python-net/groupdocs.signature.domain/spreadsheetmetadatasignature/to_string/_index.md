---
title: "to_string metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata‑signaturvärdet till en sträng med den överskrivna ToString‑metoden."
type: docs
url: /sv/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Konverterar metadata‑signaturvärdet till en sträng med den överskuggade `ToString`‑metoden.

Konverterar en boolesk egenskap till `True` eller `False`. För andra datatyper används standarddatatillhandahållaren.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Konverterar metadata-signaturen till en sträng med angivet format.

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
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
