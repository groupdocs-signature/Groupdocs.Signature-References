---
title: "QrCodeTypes sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "QR kod türleri konteyneri."
type: docs
url: /tr/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

QR kod türleri konteyneri.

QrCodeTypes türü aşağıdaki üyeleri ortaya çıkar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | Bir QR kod türü adını ayrıştırır ve karşılık gelen QRCodeType örneğini döndürür. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | Verilen ayrıştırma türü adına eşleşen QRCode türünü döndürür, ya da ad bilinmiyorsa None döndürür. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | Tüm QRCode türleri. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Aztec QR-Code Tür nesnesi. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | DataMatrix QR-Code Tür nesnesi. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | QR QR-Code Tür nesnesi. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | GS1 DataMatrix QR-Code Tür nesnesi. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | GS1 QR-Code Tür nesnesi. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | HIBC LIC QR-Code Tür nesnesi. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | HIBC LIC Data Matrix QR-Code Tür nesnesi. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | HIBC LIC Aztec QR-Code Tür nesnesi. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | HIBC PAS QR-Code Tür nesnesi. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | HIBC PAS Data Matrix QR-Code Tür nesnesi. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | HIBC PAS Aztec QR-Code Tür nesnesi. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Han Xin QR-Code Tür nesnesi. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | GS1 Han Xin QR-Code Tür nesnesi. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | RectMicroQR Tür nesnesi. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | MicroQR Tür nesnesi. |

### Örnek

```python
from groupdocs.signature.domain import QrCodeTypes

# İmza seçenekleri oluştururken QR kod türü sayımını kullanın
print(QrCodeTypes.QR)
```

### Guides
`QrCodeTypes` kullanan görev kılavuzları:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
