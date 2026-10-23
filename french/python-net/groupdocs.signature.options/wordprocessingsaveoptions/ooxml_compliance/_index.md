---
title: "propriété ooxml_compliance"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le niveau de conformité OOXML facultatif pour le document signé."
type: docs
url: /fr/python-net/groupdocs.signature.options/wordprocessingsaveoptions/ooxml_compliance/
is_root: false
weight: 2020
---


## ooxml_compliance property

Le niveau de conformité OOXML facultatif pour le document signé.

Lorsqu'elle est définie, elle remplace la conformité du document original. Lorsqu'elle est None (par défaut), la conformité du document chargé est conservée. Applicable uniquement aux formats OOXML (Docx, Docm, Dotx, Dotm, FlatOpc et variantes FlatOpc).

### Definition:
```python
@property
def ooxml_compliance(self):
    ...
@ooxml_compliance.setter
def ooxml_compliance(self, value):
    ...
```

### Voir aussi
* class [`WordProcessingSaveOptions`](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/)
