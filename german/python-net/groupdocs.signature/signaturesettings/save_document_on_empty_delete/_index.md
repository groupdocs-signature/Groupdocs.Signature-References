---
title: "save_document_on_empty_delete Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Das Flag, das bestimmt, ob das Quell‑Dokument erneut gespeichert wird, wenn die Delete‑Methode keine betroffenen Signaturen zum Entfernen hat."
type: docs
url: /de/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Das Flag, das bestimmt, ob das Quell‑Dokument erneut gespeichert wird, wenn die Delete‑Methode keine betroffenen Signaturen zum Entfernen hat.

Wenn True (Standard) ist, wird das Dokument mit einem Verlaufsprotokoll (Datum und Vorgangstyp) gespeichert, selbst wenn keine Signaturen entfernt wurden; wenn False, bleibt das Ausgangsdokument unverändert.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Siehe auch
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
