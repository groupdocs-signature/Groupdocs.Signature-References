---
title: "propriété save_document_on_empty_update"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le drapeau qui détermine si le document source est réenregistré lorsque la méthode Update n’a aucune signature à mettre à jour."
type: docs
url: /fr/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

L'indicateur qui détermine si le document source est réenregistré lorsque la méthode `Update` n'a aucune signature à mettre à jour.

Si elle est définie sur `True` (par défaut), le document est enregistré avec un journal de processus d’historique correspondant (date et type d’opération) même lorsqu’aucune signature n’est mise à jour. Lorsqu’elle est définie sur `False`, le document source n’est pas du tout modifié.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Voir aussi
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
