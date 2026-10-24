---
title: "return_content_type eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Het bestandstype van de geretourneerde afbeeldingsinhoud van de QR-Code-handtekening wanneer de eigenschap returncontent is ingeschakeld."
type: docs
url: /nl/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

Het bestandstype van de geretourneerde afbeeldingsinhoud van de QR‑Code‑handtekening wanneer de `return_content`‑eigenschap is ingeschakeld.

Standaard is het ingesteld op `None`, wat de QR-Code afbeeldingsinhoud in het oorspronkelijke formaat retourneert. Het afbeeldingsformaat wordt gespecificeerd op [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). Ondersteunde waarden zijn [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), en [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Als een niet‑ondersteund formaat wordt opgegeven, wordt de QR-Code afbeeldingsinhoud geretourneerd als een PNG.

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
