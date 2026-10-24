---
title: "propiedad return_content_type"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El tipo de archivo del contenido de imagen devuelto para una firma de código de barras cuando la propiedad returncontent está habilitada."
type: docs
url: /es/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

El tipo de archivo del contenido de imagen devuelto para una firma de código de barras cuando la propiedad `return_content` está habilitada.

Por defecto es None, lo que devuelve la imagen del código de barras en su formato original según lo especificado por [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

Los valores compatibles son [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), y [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Si se proporciona un valor distinto a estos, la imagen se devolverá en formato PNG.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
