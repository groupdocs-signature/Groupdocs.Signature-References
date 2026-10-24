---
title: "propiedad save_document_on_empty_delete"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La bandera que determina si el documento fuente se vuelve a guardar cuando el método Delete no tiene firmas afectadas que eliminar."
type: docs
url: /es/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

La bandera que determina si el documento fuente se vuelve a guardar cuando el método Delete no tiene firmas afectadas que eliminar.

Cuando es True (valor predeterminado), el documento se guarda con un registro histórico (fecha y tipo de operación) incluso si no se eliminaron firmas; cuando es False, el documento original permanece sin cambios.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Ver también
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
