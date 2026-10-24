---
title: "Classe QrCodeTypes"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il contenitore dei tipi di QR code."
type: docs
url: /it/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

Il contenitore dei tipi di QR code.

Il tipo QrCodeTypes espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | Analizza un nome di tipo QR code e restituisce l'istanza QRCodeType corrispondente. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | Restituisce il tipo QRCode corrispondente al nome di tipo fornito, oppure None se il nome è sconosciuto. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | Tutti i tipi QRCode. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Oggetto tipo Aztec QR-Code. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | Oggetto tipo DataMatrix QR-Code. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | Oggetto tipo QR QR-Code. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | Oggetto tipo GS1 DataMatrix QR-Code. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | Oggetto tipo GS1 QR-Code. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | Oggetto tipo HIBC LIC QR-Code. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | Oggetto tipo HIBC LIC Data Matrix QR-Code. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | Oggetto tipo HIBC LIC Aztec QR-Code. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | Oggetto tipo HIBC PAS QR-Code. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | Oggetto tipo HIBC PAS Data Matrix QR-Code. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | Oggetto tipo HIBC PAS Aztec QR-Code. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Oggetto tipo Han Xin QR-Code. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | Oggetto tipo GS1 Han Xin QR-Code. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | Oggetto tipo RectMicroQR. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | Oggetto tipo MicroQR. |

### Esempio

```python
from groupdocs.signature.domain import QrCodeTypes

# Utilizza l'enumerazione dei tipi QR code quando crei le opzioni di firma
print(QrCodeTypes.QR)
```

### Guides
Guide delle attività che utilizzano `QrCodeTypes`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
