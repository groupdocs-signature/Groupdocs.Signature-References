---
title: "return_content_type eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Het bestandstype van de geretourneerde afbeeldingsinhoud voor een Barcode-handtekening wanneer de returncontent property is ingeschakeld."
type: docs
url: /nl/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Het bestandstype van de geretourneerde afbeeldingsinhoud voor een Barcode‑handtekening wanneer de `return_content`‑eigenschap is ingeschakeld.

Standaard is het None, wat de barcode‑afbeelding retourneert in het oorspronkelijke formaat zoals gespecificeerd door [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

Ondersteunde waarden zijn [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), en [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Als een andere waarde wordt opgegeven, wordt de afbeelding geretourneerd in PNG‑formaat.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
