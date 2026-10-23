---
title: "to_double Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert den Wert der metadata signature in einen float."
type: docs
url: /de/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Konvertiert den Wert der metadata signature in einen float.

Löst eine Ausnahme aus, wenn der Metadatenwert nicht konvertiert werden kann. Wenn der ursprüngliche Wert zeichenkettenbasiert ist, wird die Standardsprache aus [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) verwendet.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Konvertiert zu Double.

```python
def to_double(self, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** float: The metadata signature value as a float.

### Siehe auch
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
