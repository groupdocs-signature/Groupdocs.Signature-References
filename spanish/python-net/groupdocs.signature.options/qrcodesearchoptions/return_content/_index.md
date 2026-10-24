---
title: "propiedad return_content"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El indicador que determina si el contenido de imagen del QR‑Code se devuelve para cada firma en una página del documento."
type: docs
url: /es/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/
is_root: false
weight: 2040
---


## return_content property

La bandera que determina si el contenido de imagen QR‑Code se devuelve para cada firma en una página del documento. Cuando se establece en True, los datos de imagen sin procesar se guardan en la propiedad `content` de la firma usando el formato especificado por `return_content_type`. Deshabilitado por defecto.

### Definition:
```python
@property
def return_content(self):
    ...
@return_content.setter
def return_content(self, value):
    ...
```

### Ver también
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
