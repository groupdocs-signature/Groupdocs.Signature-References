---
title: "return_content_type eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Het bestandstype van de geretourneerde afbeeldingsinhoud van de QR‑Code-handtekening wanneer de returncontent‑eigenschap is ingeschakeld."
type: docs
url: /nl/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

Het bestandstype van de geretourneerde afbeeldinginhoud van de QR‑Code handtekening wanneer de `return_content` eigenschap is ingeschakeld.

Standaard is het `None`, wat de QR‑Code‑afbeeldingsinhoud retourneert in het oorspronkelijke formaat zoals gespecificeerd door [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/).

Ondersteunde waarden zijn [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), en [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Als een niet‑ondersteund formaat wordt opgegeven, wordt de inhoud geretourneerd in PNG‑formaat.

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
