---
title: "return_content_type eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Het bestandstype van de geretourneerde afbeeldinginhoud van de Barcode-handtekening wanneer de returncontent eigenschap is ingeschakeld."
type: docs
url: /nl/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

Het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode‑handtekening wanneer de eigenschap `return_content` is ingeschakeld.

Standaard is deze ingesteld op `None`, wat betekent dat de Barcode-afbeeldingsinhoud wordt geretourneerd in het oorspronkelijke formaat. Het afbeeldingsformaat wordt gespecificeerd door [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). Ondersteunde waarden zijn [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), en [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Als een niet‑ondersteund formaat wordt opgegeven, wordt de Barcode-afbeeldingsinhoud geretourneerd in PNG-formaat.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
