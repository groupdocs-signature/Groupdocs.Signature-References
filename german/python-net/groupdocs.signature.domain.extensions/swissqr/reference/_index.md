---
title: "reference Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die Zahlungsreferenz des Gläubigers."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

Die Zahlungsreferenz des Gläubigers.

Es ist für SwissQR‑IBANs (IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx) obligatorisch. Wenn angegeben, muss die Referenz entweder eine gültige SwissQR‑Referenz (entsprechend dem ISR‑Referenzformular) oder eine gültige Gläubigerreferenz gemäß ISO 11649 ("RFxxxx") sein. Beide können zur Formatierung Leerzeichen enthalten.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Siehe auch
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
