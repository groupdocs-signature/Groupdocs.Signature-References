---
title: "return_content_type‑egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Filtypen för det returnerade bildinnehållet för en streckkodssignatur när egenskapen returncontent är aktiverad."
type: docs
url: /sv/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Filtypen för det returnerade bildinnehållet för en streckkodssignatur när egenskapen `return_content` är aktiverad.

Som standard är den None, vilket returnerar streckkodsbilden i dess ursprungliga format enligt [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

Stödda värden är [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), och [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Om ett annat värde än dessa anges, returneras bilden i PNG‑format.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Se även
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
