---
title: "to_string Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert die metadata signature in einen String."
type: docs
url: /de/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Konvertiert die metadata signature in einen String.

Konvertiert eine boolesche Eigenschaft in "True" oder "False". Für andere Datentypen wird der Standard‑Datenformat‑Provider verwendet.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Konvertiert die Metadaten‑Signatur in einen String mit dem angegebenen Format.

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
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
