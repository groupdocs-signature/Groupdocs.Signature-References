---
title: "proprietà return_content"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che determina se il contenuto immagine del QR‑Code viene restituito per ogni firma su una pagina del documento."
type: docs
url: /it/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/
is_root: false
weight: 2040
---


## return_content property

Il flag che determina se il contenuto dell'immagine QR‑Code viene restituito per ogni firma su una pagina del documento. Quando impostato su True, i dati grezzi dell'immagine sono conservati nella proprietà `content` della firma utilizzando il formato specificato da `return_content_type`. Disabilitato per impostazione predefinita.

### Definition:
```python
@property
def return_content(self):
    ...
@return_content.setter
def return_content(self, value):
    ...
```

### Vedi anche
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
