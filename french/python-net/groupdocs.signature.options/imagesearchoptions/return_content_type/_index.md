---
title: "propriété return_content_type"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le type de fichier du contenu d'image retourné lorsque la propriété returncontent est activée."
type: docs
url: /fr/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Le type de fichier du contenu image retourné lorsque la propriété `return_content` est activée.

Si non défini (par défaut `None`), le contenu de l'image est retourné dans son format d'origine tel que défini par [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). Les valeurs prises en charge sont [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), et [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Si un format non pris en charge est fourni, le format d'origine est retourné.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
