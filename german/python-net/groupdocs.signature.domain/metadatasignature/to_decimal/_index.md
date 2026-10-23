---
title: "to_decimal Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert den Wert der metadata signature in Decimal."
type: docs
url: /de/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Konvertiert den Wert der metadata signature in Decimal.

Löst eine Ausnahme aus, wenn der Metadatenwert nicht konvertiert werden konnte. Wenn der ursprüngliche Wert zeichenkettenbasiert ist, werden die Informationen zur Standardsprache aus [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) verwendet.

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Konvertiert den Wert der metadata signature in Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** The metadata signature value as Decimal.

### Siehe auch
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
