---
title: "to_date_time-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert de metadata handtekeningwaarde naar een datetime."
type: docs
url: /nl/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Converteert de metadata handtekeningwaarde naar een datetime.

Als de metadatawaarde niet kan worden geconverteerd, wordt er een uitzondering opgegooid. Wanneer de oorspronkelijke waarde een tekenreeks is, wordt de standaardcultuur van [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) gebruikt voor de conversie.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Voorbeeld

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

Converteert de metadata handtekeningwaarde naar een datetime.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Gooit een uitzondering als de metadatawaarde niet kon worden geconverteerd.

### Zie ook
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
