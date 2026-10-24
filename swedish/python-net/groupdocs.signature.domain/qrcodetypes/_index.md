---
title: "QrCodeTypes-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Behållaren för QR‑kodtyper."
type: docs
url: /sv/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

Behållaren för QR‑kodtyper.

Typen QrCodeTypes exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | Tolkar ett QR-kod-typsnamn och returnerar motsvarande QRCodeType-instans. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | Returnerar QRCode-typen som matchar det angivna tolkningsnamnet, eller None om namnet är okänt. |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | Alla QRCode-typer. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Aztec QR-Code-typobjekt. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | DataMatrix QR-Code-typobjekt. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | QR QR-Code-typobjekt. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | GS1 DataMatrix QR-Code-typobjekt. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | GS1 QR-Code-typobjekt. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | HIBC LIC QR-Code-typobjekt. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | HIBC LIC Data Matrix QR-Code-typobjekt. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | HIBC LIC Aztec QR-Code-typobjekt. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | HIBC PAS QR-Code-typobjekt. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | HIBC PAS Data Matrix QR-Code-typobjekt. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | HIBC PAS Aztec QR-Code-typobjekt. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Han Xin QR-Code-typobjekt. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | GS1 Han Xin QR-Code-typobjekt. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | RectMicroQR-typobjekt. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | MicroQR-typobjekt. |

### Exempel

```python
from groupdocs.signature.domain import QrCodeTypes

# Använd QR-kod-typens uppräkning när du skapar signeringsalternativ
print(QrCodeTypes.QR)
```

### Guides
Uppgiftsguider som använder `QrCodeTypes`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
