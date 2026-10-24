---
title: "to_string metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata-signaturen till en sträng."
type: docs
url: /sv/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

Konverterar metadata-signaturen till en sträng.

Konverterar en boolesk egenskap till "True" eller "False". För andra datatyper kommer standarddatakonverteringsleverantören att användas.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

Konverterar metadata-signaturen till en sträng med angivet format.

Konverterar en boolesk egenskap till "True" eller "False". Information om standardkultur egenskapen kommer att hämtas från SignatureSettings‑egenskaperna [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| format | `str` | Dataformatsträng. |

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

**Returns:** The metadata signature value as a string.

### Se även
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
