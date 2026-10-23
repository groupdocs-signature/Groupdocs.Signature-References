---
title: "return_content_type Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Der Dateityp des zurückgegebenen Bildinhalts, wenn die returncontent-Eigenschaft aktiviert ist."
type: docs
url: /de/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Der Dateityp des zurückgegebenen Bildinhalts, wenn die Eigenschaft `return_content` aktiviert ist.

Wenn nicht gesetzt (Standard `None`), wird der Bildinhalt in seinem ursprünglichen Format zurückgegeben, wie von [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) definiert. Unterstützte Werte sind [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), und [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Wird ein nicht unterstütztes Format angegeben, wird das ursprüngliche Format zurückgegeben.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
