---
title: "proprietà save_document_on_empty_update"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che determina se il documento originale viene risalvato quando il metodo Update non ha firme da aggiornare."
type: docs
url: /it/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

Il flag che determina se il documento sorgente viene risalvato quando il metodo `Update` non ha firme da aggiornare.

Se impostato su `True` (predefinito), il documento viene salvato con un registro di processo storico corrispondente (data e tipo di operazione) anche quando non vengono aggiornate firme. Quando impostato su `False`, il documento originale non viene modificato affatto.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Vedi anche
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
