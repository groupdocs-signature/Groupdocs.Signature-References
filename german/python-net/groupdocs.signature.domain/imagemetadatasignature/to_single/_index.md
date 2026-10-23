---
title: "to_single Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert zu float."
type: docs
url: /de/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Konvertiert zu float.

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte. Ist der ursprüngliche Wert zeichenbasiert, werden die Standardkultureigenschaften von [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) verwendet.

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Konvertiert den Wert der metadata signature in einen float.

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.

```python
def to_single(self, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** float: The metadata signature value as a float.

### Siehe auch
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
