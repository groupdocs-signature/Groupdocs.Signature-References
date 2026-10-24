---
title: "propiedad return_content_type"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El tipo de archivo del contenido de imagen devuelto cuando la propiedad returncontent está habilitada."
type: docs
url: /es/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

El tipo de archivo del contenido de imagen devuelto cuando la propiedad `return_content` está habilitada.

Si no se establece (por defecto `None`), el contenido de la imagen se devuelve en su formato original según lo definido por [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). Los valores compatibles son [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), y [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Si se proporciona un formato no compatible, se devuelve el formato original.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
