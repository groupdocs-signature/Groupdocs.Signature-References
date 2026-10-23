---
title: "return_content_type Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Der Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur, wenn die returncontent‑Eigenschaft aktiviert ist."
type: docs
url: /de/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

Der Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur, wenn die Eigenschaft `return_content` aktiviert ist.

Standardmäßig ist es auf `None` gesetzt, was den QR‑Code‑Bildinhalt im Originalformat zurückgibt. Das Bildformat wird bei [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) angegeben. Unterstützte Werte sind [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), und [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Wenn ein nicht unterstütztes Format angegeben wird, wird der QR‑Code‑Bildinhalt als PNG zurückgegeben.

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
