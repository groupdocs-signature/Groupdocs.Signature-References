---
title: "return_content_type Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Der Dateityp des zurückgegebenen Bildinhalts für eine Barcode‑Signatur, wenn die returncontent‑Eigenschaft aktiviert ist."
type: docs
url: /de/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Der Dateityp des zurückgegebenen Bildinhalts für eine Barcode-Signatur, wenn die `return_content`-Eigenschaft aktiviert ist.

Standardmäßig ist es None, wodurch das Barcode‑Bild in seinem ursprünglichen Format zurückgegeben wird, wie in [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) angegeben.

Unterstützte Werte sind [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), und [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Wird ein anderer Wert angegeben, wird das Bild im PNG‑Format zurückgegeben.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Siehe auch
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
