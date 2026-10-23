---
title: "to_date_time Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert den Metadaten‑Signaturwert in ein datetime.datetime."
type: docs
url: /de/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Konvertiert den Metadaten‑Signaturwert zu einem `datetime.datetime`.

Wirft eine Ausnahme, wenn der metadata‑Wert nicht konvertiert werden kann. Wenn der ursprüngliche Wert string‑basiert ist, wird die Standardsprache aus [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) verwendet.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Konvertiert den Metadaten‑Signaturwert zu einem `datetime`.

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Siehe auch
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
