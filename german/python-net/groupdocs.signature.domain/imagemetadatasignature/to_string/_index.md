---
title: "to_string Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert den Metadaten‑Signaturwert zu einem String."
type: docs
url: /de/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Konvertiert den Metadaten‑Signaturwert zu einem String.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Konvertiert den Metadaten‑Signaturwert zu einem String unter Verwendung des angegebenen Formats.

Konvertiert eine boolesche Eigenschaft in "True" oder "False". Die Standardkultureinstellungen von [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) werden verwendet.

```python
def to_string(self, format):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| format | `str` | Datenformat‑Zeichenkette. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Konvertiert in einen String mit dem angegebenen Format.

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
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
