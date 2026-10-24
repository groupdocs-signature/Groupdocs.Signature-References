---
title: "propiedad return_content_type"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El tipo de archivo del contenido de imagen devuelto de la firma Barcode cuando la propiedad returncontent está habilitada."
type: docs
url: /es/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

El tipo de archivo del contenido de imagen devuelto de la firma Barcode cuando la propiedad `return_content` está habilitada.

Por defecto se establece en `None`, lo que significa que el contenido de la imagen Barcode se devuelve en su formato original. El formato de la imagen se especifica mediante [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). Los valores compatibles son [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), y [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Si se proporciona un formato que no es compatible, el contenido de la imagen Barcode se devolverá en formato PNG.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
