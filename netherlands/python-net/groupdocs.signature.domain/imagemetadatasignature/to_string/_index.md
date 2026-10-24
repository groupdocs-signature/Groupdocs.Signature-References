---
title: "to_string-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Converteert de metadata‑handtekeningwaarde naar een string."
type: docs
url: /nl/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Converteert de metadata‑handtekeningwaarde naar een string.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Converteert de metadata‑handtekeningwaarde naar een string met het opgegeven formaat.

Converteert een booleaanse eigenschap naar "True" of "False". De standaardcultuurinformatie van [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) wordt gebruikt.

```python
def to_string(self, format):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| format | `str` | Gegevensformaatreeks. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converteert naar een string met het opgegeven formaat.

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
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
