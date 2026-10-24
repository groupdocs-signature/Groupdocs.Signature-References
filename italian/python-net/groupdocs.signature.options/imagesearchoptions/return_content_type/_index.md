---
title: "proprietà return_content_type"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il tipo di file del contenuto immagine restituito quando la proprietà returncontent è abilitata."
type: docs
url: /it/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Il tipo di file del contenuto immagine restituito quando la proprietà `return_content` è abilitata.

Se non impostato (predefinito `None`), il contenuto dell'immagine viene restituito nel suo formato originale come definito da [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). I valori supportati sono [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), e [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Se viene fornito un formato non supportato, viene restituito il formato originale.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
