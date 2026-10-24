---
title: "return_content_type‑egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Filtypen för det returnerade bildinnehållet när egenskapen returncontent är aktiverad."
type: docs
url: /sv/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Filtypen för det returnerade bildinnehållet när egenskapen `return_content` är aktiverad.

Om den inte är angiven (standard `None`), returneras bildinnehållet i sitt ursprungliga format enligt [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). Stödda värden är [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), och [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Om ett format som inte stöds anges, returneras det ursprungliga formatet.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
