---
title: "propriété reference"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "La référence de paiement du créancier."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

La référence de paiement du créancier.

Il est obligatoire pour les IBAN SwissQR (IBAN dans la plage CHxx30000xxxxxx à CHxx31999xxxxx). Si spécifié, la référence doit être soit une référence SwissQR valide (correspondant au formulaire de référence ISR), soit une référence créancier valide selon la norme ISO 11649 ("RFxxxx"). Les deux peuvent contenir des espaces pour le formatage.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Voir aussi
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
