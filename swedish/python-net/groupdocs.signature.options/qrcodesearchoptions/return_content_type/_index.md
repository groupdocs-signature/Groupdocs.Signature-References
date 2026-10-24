---
title: "return_content_type‑egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Filtypen för det returnerade bildinnehållet i QR-Code-signaturen när egenskapen returncontent är aktiverad."
type: docs
url: /sv/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

Filtypen för det returnerade bildinnehållet i QR‑Code‑signaturen när egenskapen `return_content` är aktiverad.

Som standard är den inställd på `None`, vilket returnerar QR-Code-bildinnehållet i dess ursprungliga format. Bildformatet anges på [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). Stödda värden är [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), och [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Om ett format som inte stöds anges, returneras QR-Code-bildinnehållet som en PNG.

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
