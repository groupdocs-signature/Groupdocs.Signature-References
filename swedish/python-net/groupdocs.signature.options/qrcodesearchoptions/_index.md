---
title: "QrCodeSearchOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar sökalternativ för QR‑Kod‑signaturer."
type: docs
url: /sv/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

Representerar sökalternativ för QR‑Kod‑signaturer.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

Typen QrCodeSearchOptions visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | Initierar en ny instans av QRCodeSearchOptions-klassen med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | Initierar en ny instans av QRCodeSearchOptions-klassen med kodningstypvärde. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | Initierar en ny instans av klassen QRCodeSearchOptions med kodningstyp och textvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | Implementeringen av [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) som används för att koda och avkoda QR-Code‑signaturens text‑ eller datapropertys. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | Kodningstypen att söka efter QR‑koder. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | QR‑Code‑textmatchningstypen som används under sökning. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | Flaggan som bestämmer om QR‑Code‑bildinnehåll returneras för varje signatur på en dokumentsida. När den är satt till True behålls råbilddata i signaturens `content`‑egenskap med det format som anges av `return_content_type`. Inaktiverad som standard. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | Filtypen för det returnerade bildinnehållet i QR‑Code‑signaturen när egenskapen `return_content` är aktiverad. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | QR‑Code‑signaturtexten att söka efter och matcha. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Flaggan som anger om varje dokumentsida ska genomsökas. Standardvärdet är True. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Dokumentsidans nummer för sökning (valfritt). (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Alternativen för att ange sidor för signatursökning. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Flaggan som anger om formens position i dokumentlayouten ska returneras. Endast tillgänglig för Word‑dokument. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Flaggan för att endast returnera signaturer markerade som `IsSignature`. Standardvärdet är `False`, vilket innebär att alla signaturer som matchar de angivna kriterierna returneras. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
