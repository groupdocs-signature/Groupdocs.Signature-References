---
title: "propiedad reference"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La referencia de pago del acreedor."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

La referencia de pago del acreedor.

Es obligatorio para los IBAN SwissQR (IBAN en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx). Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente al formulario de referencia ISR) o una referencia de acreedor válida según ISO 11649 ("RFxxxx"). Ambas pueden contener espacios para el formato.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### Ver también
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
