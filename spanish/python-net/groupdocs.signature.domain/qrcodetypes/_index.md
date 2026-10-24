---
title: "Clase QrCodeTypes"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El contenedor de tipos de código QR."
type: docs
url: /es/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

El contenedor de tipos de código QR.

El tipo QrCodeTypes expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | Analiza un nombre de tipo de código QR y devuelve la instancia correspondiente de QRCodeType. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | Devuelve el tipo QRCode que coincide con el nombre de tipo de análisis proporcionado, o None si el nombre es desconocido. |

### Campos
| Campo | Descripción |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | Todos los tipos QRCode. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Objeto de tipo QR-Code Aztec. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | Objeto de tipo QR-Code DataMatrix. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | Objeto de tipo QR-Code QR. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | Objeto de tipo QR-Code GS1 DataMatrix. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | Objeto de tipo QR-Code GS1. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | Objeto de tipo QR-Code HIBC LIC. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | Objeto de tipo QR-Code HIBC LIC Data Matrix. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | Objeto de tipo QR-Code HIBC LIC Aztec. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | Objeto de tipo QR-Code HIBC PAS. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | Objeto de tipo QR-Code HIBC PAS Data Matrix. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | Objeto de tipo QR-Code HIBC PAS Aztec. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Objeto de tipo QR-Code Han Xin. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | Objeto de tipo QR-Code GS1 Han Xin. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | Objeto de tipo RectMicroQR. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | Objeto de tipo MicroQR. |

### Ejemplo

```python
from groupdocs.signature.domain import QrCodeTypes

# Utiliza la enumeración de tipos de código QR al crear opciones de firma
print(QrCodeTypes.QR)
```

### Guides
Guías de tareas que utilizan `QrCodeTypes`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
