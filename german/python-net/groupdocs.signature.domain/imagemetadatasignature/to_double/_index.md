---
title: "to_double Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert zu einem Float."
type: docs
url: /de/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Konvertiert zu einem Float.

Wirft eine Ausnahme, wenn der metadata‑Wert nicht konvertiert werden kann. Wenn der ursprüngliche Wert string‑basiert ist, wird die Standardsprache aus [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) verwendet.

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Konvertiert den Wert der metadata signature in einen float.

Verwendet den angegebenen Format‑Daten‑Provider, um die Konvertierung durchzuführen.

```python
def to_double(self, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** float: The metadata signature value as a float.

### Siehe auch
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
