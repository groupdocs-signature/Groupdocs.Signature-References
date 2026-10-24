---
title: "return_content_type‑egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Filtypen för det returnerade bildinnehållet för Barcode‑signaturen när returncontent‑egenskapen är aktiverad."
type: docs
url: /sv/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

Filtypen för det returnerade bildinnehållet för Barcode‑signaturen när egenskapen `return_content` är aktiverad.

Som standard är den satt till `None`, vilket betyder att Barcode‑bildinnehållet returneras i sitt ursprungliga format. Bildformatet anges av [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). Stödda värden är [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), och [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Om ett format som inte stöds anges, kommer Barcode‑bildinnehållet att returneras i PNG‑format.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
