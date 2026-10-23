---
title: "to_decimal Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert zu Decimal."
type: docs
url: /de/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Konvertiert zu Decimal.

Löst eine Ausnahme aus, wenn der Metadatenwert nicht konvertiert werden kann. Wenn der ursprüngliche Wert zeichenkettenbasiert ist, wird die Standardsprache aus [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) verwendet.

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Konvertiert den Metadaten‑Signaturwert zu einem Dezimalwert.

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** float: The metadata signature value as a decimal.

### Siehe auch
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
