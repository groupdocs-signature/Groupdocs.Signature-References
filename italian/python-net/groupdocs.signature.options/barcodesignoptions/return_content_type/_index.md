---
title: "proprietà return_content_type"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà returncontent è abilitata."
type: docs
url: /it/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

Il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà `return_content` è abilitata.

Per impostazione predefinita è impostato su `None`, il che significa che il contenuto dell'immagine Barcode viene restituito nel suo formato originale. Il formato dell'immagine è specificato da [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). I valori supportati sono [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), e [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Se viene fornito un formato non supportato, il contenuto dell'immagine Barcode verrà restituito in formato PNG.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
