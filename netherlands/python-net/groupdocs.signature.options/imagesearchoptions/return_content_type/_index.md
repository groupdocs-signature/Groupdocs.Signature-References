---
title: "return_content_type eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Het bestandstype van de geretourneerde afbeeldingsinhoud wanneer de returncontent eigenschap is ingeschakeld."
type: docs
url: /nl/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Het bestandstype van de geretourneerde afbeeldingsinhoud wanneer de eigenschap `return_content` is ingeschakeld.

Indien niet ingesteld (standaard `None`), wordt de afbeeldingsinhoud geretourneerd in het oorspronkelijke formaat zoals gedefinieerd door [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). Ondersteunde waarden zijn [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), en [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Als een niet‑ondersteund formaat wordt opgegeven, wordt het oorspronkelijke formaat geretourneerd.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Zie ook
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
