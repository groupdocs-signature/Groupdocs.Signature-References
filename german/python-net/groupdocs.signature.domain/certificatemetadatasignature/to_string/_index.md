---
title: "to_string Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Konvertiert die Metadaten‑Signatur in einen String mittels der überschriebenen ToString‑Methode."
type: docs
url: /de/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Konvertiert die Metadaten‑Signatur in einen String mittels der überschriebenen ToString‑Methode.

Konvertiert eine boolesche Eigenschaft in "True" oder "False". Für andere Datentypen wird der Standard‑Datenformat‑Provider verwendet.

```python
def to_string(self):
    ...
```

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

**Returns:** The metadata signature value as a string.

### Siehe auch
* class [`CertificateMetadataSignature`](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/)
