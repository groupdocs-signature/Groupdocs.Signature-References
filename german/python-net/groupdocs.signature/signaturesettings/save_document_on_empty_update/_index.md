---
title: "save_document_on_empty_update Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Das Flag, das bestimmt, ob das Ausgangsdokument erneut gespeichert wird, wenn die Update-Methode keine zu aktualisierenden Signaturen hat."
type: docs
url: /de/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

Das Flag, das bestimmt, ob das Quell‑Dokument erneut gespeichert wird, wenn die `Update`‑Methode keine Signaturen zum Aktualisieren hat.

Wenn auf `True` (Standard) gesetzt, wird das Dokument mit einem entsprechenden Verlaufsprozessprotokoll (Datum und Vorgangstyp) gespeichert, selbst wenn keine Signaturen aktualisiert werden. Wenn auf `False` gesetzt, wird das Ausgangsdokument überhaupt nicht geändert.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Siehe auch
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
