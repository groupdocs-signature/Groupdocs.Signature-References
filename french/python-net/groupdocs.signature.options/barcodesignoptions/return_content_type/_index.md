---
title: "propriété return_content_type"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le type de fichier du contenu d’image retourné de la signature Barcode lorsque la propriété returncontent est activée."
type: docs
url: /fr/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

Le type de fichier du contenu d'image retourné de la signature Barcode lorsque la propriété `return_content` est activée.

Par défaut, il est défini sur `None`, ce qui signifie que le contenu de l’image Barcode est retourné dans son format d’origine. Le format d’image est spécifié par [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). Les valeurs prises en charge sont [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), et [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Si un format non pris en charge est fourni, le contenu de l’image Barcode sera retourné au format PNG.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Voir aussi
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
