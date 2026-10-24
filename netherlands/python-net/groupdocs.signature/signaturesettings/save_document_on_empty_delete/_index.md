---
title: "save_document_on_empty_delete eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De vlag die bepaalt of het brondocument opnieuw wordt opgeslagen wanneer de Delete‑methode geen getroffen handtekeningen heeft om te verwijderen."
type: docs
url: /nl/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

De vlag die bepaalt of het brondocument opnieuw wordt opgeslagen wanneer de Delete‑methode geen getroffen handtekeningen heeft om te verwijderen.

Wanneer True (standaard), wordt het document opgeslagen met een historielog (datum en type bewerking) zelfs als er geen handtekeningen zijn verwijderd; wanneer False, blijft het brondocument ongewijzigd.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Zie ook
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
