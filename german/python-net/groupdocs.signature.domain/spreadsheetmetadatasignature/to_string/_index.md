---
title: "to_string Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert den Metadaten‑Signaturwert in einen String, indem die überschriebene ToString‑Methode verwendet wird."
type: docs
url: /de/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Konvertiert den Metadaten-Signaturwert in einen String mittels der überschriebenen `ToString`-Methode.

Konvertiert eine boolesche Eigenschaft in `True` oder `False`. Für andere Datentypen wird der Standard‑Datenformatanbieter verwendet.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Konvertiert die metadata signature in einen String unter Verwendung des angegebenen Formats.

Konvertiert eine boolesche Eigenschaft in "True" oder "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| format | `str` | Datenformat‑Zeichenkette. |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** str: The metadata signature value as a string.

### Siehe auch
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
