---
title: "referentie-eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De betalingsreferentie van de crediteur."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

De betalingsreferentie van de crediteur.

Het is verplicht voor SwissQR-IBAN's (IBAN's in het bereik CHxx30000xxxxxx tot CHxx31999xxxxx). Indien gespecificeerd, moet de referentie een geldige SwissQR-referentie zijn (overeenkomend met ISR-referentieformulier) of een geldige crediteurreferentie volgens ISO 11649 (\"RFxxxx\"). Beide mogen spaties bevatten voor opmaak.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Zie ook
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
