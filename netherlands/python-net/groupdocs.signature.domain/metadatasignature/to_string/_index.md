---
title: "to_string-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert de metadata handtekening naar een string."
type: docs
url: /nl/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

Converteert de metadata handtekening naar een string.

Converteert een booleaanse eigenschap naar "True" of "False". Voor andere gegevenstypen wordt de standaardgegevensformaatprovider gebruikt.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

Converteert de metadata handtekening naar een string met het opgegeven formaat.

Converteert een booleaanse eigenschap naar "True" of "False". Informatie over de standaardcultuur wordt gehaald uit de SignatureSettings‑eigenschappen [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| format | `str` | Gegevensformaatreeks. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converteert naar string met opgegeven formaat.

Converteert een booleaanse eigenschap naar "True" of "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| format | `str` | Gegevensformaatreeks. |
| provider | `System.IFormatProvider` | Gegevensprovider formatteren voor gebruik bij gegevensconversie‑bewerkingen. |

**Returns:** The metadata signature value as a string.

### Zie ook
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
