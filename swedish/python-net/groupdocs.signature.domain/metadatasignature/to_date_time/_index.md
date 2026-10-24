---
title: "to_date_time metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Konverterar metadata-signaturens värde till ett datetime."
type: docs
url: /sv/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Konverterar metadata-signaturens värde till ett datetime.

Om metadata‑värdet inte kan konverteras kastas ett undantag. När det ursprungliga värdet är sträng‑baserat används standardkulturen från [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) för konverteringen.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Konverterar metadata-signaturens värde till ett datetime.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Formatera dataleverantör för att användas i datakonverteringsoperationer. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Kastar ett undantag om metadata‑värdet inte kunde konverteras.

### Se även
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
