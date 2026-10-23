---
title: "return_content_type Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Der Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur, wenn die returncontent‑Eigenschaft aktiviert ist."
type: docs
url: /de/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

Der Dateityp des zurückgegebenen Bildinhalts der Barcode-Signatur, wenn die Eigenschaft `return_content` aktiviert ist.

Standardmäßig ist es auf `None` gesetzt, was bedeutet, dass der Barcode‑Bildinhalt in seinem Originalformat zurückgegeben wird. Das Bildformat wird durch [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) angegeben. Unterstützte Werte sind [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), und [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Wird ein nicht unterstütztes Format angegeben, wird der Barcode‑Bildinhalt im PNG‑Format zurückgegeben.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
