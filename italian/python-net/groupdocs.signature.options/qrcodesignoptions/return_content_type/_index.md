---
title: "proprietà return_content_type"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il tipo di file del contenuto immagine restituito della firma QR‑Code quando la proprietà returncontent è abilitata."
type: docs
url: /it/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

Il tipo di file del contenuto immagine restituito della firma QR‑Code quando la proprietà `return_content` è abilitata.

Per impostazione predefinita è `None`, che restituisce il contenuto dell'immagine QR‑Code nel suo formato originale come specificato da [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/).

I valori supportati sono [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), e [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Se viene fornito un formato non supportato, il contenuto viene restituito in formato PNG.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Vedi anche
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
