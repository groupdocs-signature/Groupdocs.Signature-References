---
title: "proprietà save_document_on_empty_delete"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che determina se il documento sorgente viene risalvato quando il metodo Delete non ha firme interessate da rimuovere."
type: docs
url: /it/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Il flag che determina se il documento sorgente viene risalvato quando il metodo Delete non ha firme interessate da rimuovere.

Quando True (predefinito), il documento viene salvato con un registro storico (data e tipo di operazione) anche se non sono state rimosse firme; quando False, il documento originale rimane invariato.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Vedi anche
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
