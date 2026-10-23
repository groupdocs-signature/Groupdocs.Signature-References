---
title: "propriété return_content_type"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le type de fichier du contenu image retourné de la signature QR‑Code lorsque la propriété returncontent est activée."
type: docs
url: /fr/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

Le type de fichier du contenu image retourné de la signature QR‑Code lorsque la propriété `return_content` est activée.

Par défaut, il est `None`, ce qui renvoie le contenu image du QR‑Code dans son format original tel que spécifié par [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/).

Les valeurs prises en charge sont [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), et [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Si un format non pris en charge est fourni, le contenu est renvoyé au format PNG.

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
