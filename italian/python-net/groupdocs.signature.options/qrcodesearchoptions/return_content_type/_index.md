---
title: "proprietà return_content_type"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà returncontent è abilitata."
type: docs
url: /it/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

Il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà `return_content` è abilitata.

Per impostazione predefinita è impostato su `None`, il che restituisce il contenuto immagine del QR-Code nel suo formato originale. Il formato immagine è specificato in [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). I valori supportati sono [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), e [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Se viene fornito un formato non supportato, il contenuto immagine del QR-Code viene restituito come PNG.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Vedi anche
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
