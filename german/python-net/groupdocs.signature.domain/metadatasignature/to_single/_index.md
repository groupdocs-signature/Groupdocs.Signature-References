---
title: "to_single Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert den Wert der metadata signature in einen float."
type: docs
url: /de/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Konvertiert den Wert der metadata signature in einen float.

Wirft eine Ausnahme, wenn der metadata‑Wert nicht konvertiert werden kann. Wenn der ursprüngliche Wert string‑basiert ist, wird die Standardsprache aus [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) verwendet.

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Konvertiert zu float.

```python
def to_single(self, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** float: The Metadata Signature value as float.

### Siehe auch
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
