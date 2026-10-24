---
title: "reference-egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Borgenärens betalningsreferens."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

Borgenärens betalningsreferens.

Det är obligatoriskt för SwissQR-IBAN:n (IBAN:n i intervallet CHxx30000xxxxxx till CHxx31999xxxxx). Om angivet måste referensen vara antingen en giltig SwissQR-referens (motsvarande ISR-referensform) eller en giltig borgenärsreferens enligt ISO 11649 (\"RFxxxx\"). Båda kan innehålla mellanslag för formatering.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Se även
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
