---
title: "proprietà return_content_type"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il tipo di file del contenuto immagine restituito per una firma Barcode quando la proprietà returncontent è abilitata."
type: docs
url: /it/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Il tipo di file del contenuto immagine restituito per una firma Barcode quando la proprietà `return_content` è abilitata.

Per impostazione predefinita è None, il che restituisce l'immagine del codice a barre nel suo formato originale come specificato da [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

I valori supportati sono [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), e [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Se viene fornito un valore diverso da questi, l'immagine verrà restituita in formato PNG.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
