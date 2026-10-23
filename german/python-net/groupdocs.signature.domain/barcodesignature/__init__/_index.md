---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert ein BarcodeSignature-Objekt mit einer Signaturkennung, die nach einem Suchvorgang erhalten wurde."
type: docs
url: /de/python-net/groupdocs.signature.domain/barcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

Initialisiert ein BarcodeSignature-Objekt mit einem Signatur‑Identifikator, der nach einem Suchvorgang erhalten wurde. Der Identifikator wird verwendet, um zusätzliche Eigenschaften für diese Signatur aus der Signatur‑Informationsebene des Dokuments abzurufen.

```python
def __init__(self, signature_id):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature_id | `str` | Einzigartige Signaturkennung, die durch die `Sign`- oder `Search`-Methode von `Signature` erhalten wurde. |

### Siehe auch
* class [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature/)
