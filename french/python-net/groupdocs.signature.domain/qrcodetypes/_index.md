---
title: "Classe QrCodeTypes"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le conteneur des types de QR code."
type: docs
url: /fr/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

Le conteneur des types de QR code.

Le type QrCodeTypes expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | Analyse un nom de type de code QR et renvoie l'instance QRCodeType correspondante. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | Renvoie le type QRCode correspondant au nom de type d'analyse fourni, ou None si le nom est inconnu. |

### Champs
| Champ | Description |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | Tous les types QRCode. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Objet de type QR-Code Aztec. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | Objet de type QR-Code DataMatrix. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | Objet de type QR-Code QR. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | Objet de type QR-Code GS1 DataMatrix. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | Objet de type QR-Code GS1. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | Objet de type QR-Code HIBC LIC. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | Objet de type QR-Code HIBC LIC Data Matrix. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | Objet de type QR-Code HIBC LIC Aztec. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | Objet de type QR-Code HIBC PAS. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | Objet de type QR-Code HIBC PAS Data Matrix. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | Objet de type QR-Code HIBC PAS Aztec. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Objet de type QR-Code Han Xin. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | Objet de type QR-Code GS1 Han Xin. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | Objet de type RectMicroQR. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | Objet de type MicroQR. |

### Exemple

```python
from groupdocs.signature.domain import QrCodeTypes

# Utilisez l'énumération de type de code QR lors de la création des options de signature
print(QrCodeTypes.QR)
```

### Guides
Guides de tâches qui utilisent `QrCodeTypes`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
