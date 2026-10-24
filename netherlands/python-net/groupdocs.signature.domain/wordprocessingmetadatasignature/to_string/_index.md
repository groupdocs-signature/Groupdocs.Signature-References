---
title: "to_string-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert de metadata handtekening naar een string."
type: docs
url: /nl/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Converteert de metadata handtekening naar een string.

Converteert een booleaanse eigenschap naar "True" of "False". Voor andere gegevenstypen wordt de standaardgegevensformaatprovider gebruikt.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converteert de metadatavertekening naar een string met het opgegeven formaat.

Converteert een booleaanse eigenschap naar "True" of "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| format | `str` | Gegevensformaatreeks. |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** str: The metadata signature value as a string.

### Zie ook
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
