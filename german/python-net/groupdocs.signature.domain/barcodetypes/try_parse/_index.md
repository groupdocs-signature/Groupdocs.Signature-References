---
title: "try_parse Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Gibt den Barcode‑Typ zurück, der dem angegebenen Parsertypnamen entspricht."
type: docs
url: /de/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Gibt den Barcode‑Typ zurück, der dem angegebenen Parsertypnamen entspricht.

Wenn der Name unbekannt ist, gibt die Methode None zurück, anstatt eine Ausnahme auszulösen.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| parsing_type | `str` | Quellzeichenkette des Barcode‑Typnamens. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Siehe auch
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
