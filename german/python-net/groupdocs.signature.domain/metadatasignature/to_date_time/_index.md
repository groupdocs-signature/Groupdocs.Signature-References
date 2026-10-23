---
title: "to_date_time Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert den Wert der metadata signature in ein datetime."
type: docs
url: /de/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Konvertiert den Wert der metadata signature in ein datetime.

Wenn der Metadatenwert nicht konvertiert werden kann, wird eine Ausnahme ausgelöst. Wenn der ursprüngliche Wert zeichenkettenbasiert ist, wird die Standardsprache aus [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) für die Konvertierung verwendet.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Konvertiert den Wert der metadata signature in ein datetime.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format‑Datenprovider zur Verwendung bei Datenkonvertierungsoperationen. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Wirft eine Ausnahme, wenn der Metadatenwert nicht konvertiert werden konnte.

### Siehe auch
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
