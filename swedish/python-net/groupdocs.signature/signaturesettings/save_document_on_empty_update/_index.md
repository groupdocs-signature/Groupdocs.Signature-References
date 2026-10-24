---
title: "save_document_on_empty_update egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Flaggan som bestämmer om källdokumentet ska sparas om när Update‑metoden inte har några signaturer att uppdatera."
type: docs
url: /sv/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

Flaggan som bestämmer om källdokumentet sparas om när `Update`-metoden inte har några signaturer att uppdatera.

Om den är satt till `True` (standard) sparas dokumentet med en motsvarande historikprocesslogg (datum och operationstyp) även när inga signaturer uppdateras. När den är satt till `False` ändras källdokumentet inte alls.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Se även
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
