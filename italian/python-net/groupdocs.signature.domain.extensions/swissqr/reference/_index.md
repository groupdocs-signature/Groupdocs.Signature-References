---
title: "proprietà reference"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il riferimento di pagamento del creditore."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

Il riferimento di pagamento del creditore.

È obbligatorio per gli IBAN SwissQR (IBAN nell'intervallo CHxx30000xxxxxx fino a CHxx31999xxxxx). Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente al modulo di riferimento ISR) o un riferimento creditore valido secondo ISO 11649 (\"RFxxxx\"). Entrambi possono contenere spazi per la formattazione.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Vedi anche
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
