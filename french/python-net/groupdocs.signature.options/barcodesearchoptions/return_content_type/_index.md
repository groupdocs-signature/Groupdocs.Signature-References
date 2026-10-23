---
title: "propriété return_content_type"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le type de fichier du contenu d'image retourné pour une signature de code-barres lorsque la propriété returncontent est activée."
type: docs
url: /fr/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Le type de fichier du contenu image retourné pour une signature Barcode lorsque la propriété `return_content` est activée.

Par défaut, il est None, ce qui renvoie l'image du code-barres dans son format d'origine tel que spécifié par [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

Les valeurs prises en charge sont [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), et [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Si une valeur différente de celles-ci est fournie, l'image sera renvoyée au format PNG.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
