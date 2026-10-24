---
title: "save_document_on_empty_delete egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Flaggan som bestämmer om källdokumentet sparas om när Delete-metoden inte har några påverkade signaturer att ta bort."
type: docs
url: /sv/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Flaggan som bestämmer om källdokumentet sparas om när Delete-metoden inte har några påverkade signaturer att ta bort.

När den är True (standard) sparas dokumentet med en historiklogg (datum och operationstyp) även om inga signaturer har tagits bort; när den är False lämnas källdokumentet oförändrat.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Se även
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
