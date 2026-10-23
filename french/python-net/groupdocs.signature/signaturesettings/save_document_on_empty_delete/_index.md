---
title: "propriété save_document_on_empty_delete"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "L'indicateur qui détermine si le document source est réenregistré lorsque la méthode Delete n'a aucune signature affectée à supprimer."
type: docs
url: /fr/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

L'indicateur qui détermine si le document source est réenregistré lorsque la méthode Delete n'a aucune signature affectée à supprimer.

Lorsque True (par défaut), le document est enregistré avec un journal d’historique (date et type d’opération) même si aucune signature n’a été supprimée ; lorsque False, le document source reste inchangé.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Voir aussi
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
