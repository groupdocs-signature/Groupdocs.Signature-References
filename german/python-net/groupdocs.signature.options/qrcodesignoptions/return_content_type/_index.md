---
title: "return_content_type Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Der Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur, wenn die Eigenschaft returncontent aktiviert ist."
type: docs
url: /de/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

Der Dateityp des zurückgegebenen Bildinhalts der QR‑Code-Signatur, wenn die Eigenschaft `return_content` aktiviert ist.

Standardmäßig ist es `None`, was den QR‑Code‑Bildinhalt in seinem ursprünglichen Format zurückgibt, wie in [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) angegeben.

Unterstützte Werte sind [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), und [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Wird ein nicht unterstütztes Format angegeben, wird der Inhalt im PNG‑Format zurückgegeben.

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
