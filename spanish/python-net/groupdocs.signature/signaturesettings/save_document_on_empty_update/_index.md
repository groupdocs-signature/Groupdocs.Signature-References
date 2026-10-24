---
title: "propiedad save_document_on_empty_update"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La bandera que determina si el documento fuente se vuelve a guardar cuando el método Update no tiene firmas para actualizar."
type: docs
url: /es/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

La bandera que determina si el documento fuente se vuelve a guardar cuando el método `Update` no tiene firmas para actualizar.

Si se establece en `True` (valor predeterminado), el documento se guarda con un registro de proceso histórico correspondiente (fecha y tipo de operación) incluso cuando no se actualizan firmas. Cuando se establece en `False`, el documento fuente no se modifica en absoluto.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Ver también
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
