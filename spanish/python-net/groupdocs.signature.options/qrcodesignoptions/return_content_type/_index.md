---
title: "propiedad return_content_type"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El tipo de archivo del contenido de imagen devuelto de la firma QR‑Code cuando la propiedad returncontent está habilitada."
type: docs
url: /es/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

El tipo de archivo del contenido de imagen devuelto de la firma QR‑Code cuando la propiedad `return_content` está habilitada.

Por defecto es `None`, lo que devuelve el contenido de imagen QR‑Code en su formato original según lo especificado por [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/).

Los valores compatibles son [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), y [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Si se proporciona un formato no compatible, el contenido se devuelve en formato PNG.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Ver también
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
