---
title: "kelas QrCodeTypes"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Kontainer tipe kode QR."
type: docs
url: /id/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

Kontainer tipe kode QR.

Tipe QrCodeTypes menampilkan anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | Menganalisis nama tipe kode QR dan mengembalikan instance QRCodeType yang sesuai. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | Mengembalikan tipe QRCode yang cocok dengan nama tipe parsing yang diberikan, atau None jika nama tidak dikenal. |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | Semua tipe QRCode. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Objek tipe Aztec QR-Code. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | Objek tipe DataMatrix QR-Code. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | Objek tipe QR QR-Code. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | Objek tipe GS1 DataMatrix QR-Code. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | Objek tipe GS1 QR-Code. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | Objek tipe HIBC LIC QR-Code. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | Objek tipe HIBC LIC Data Matrix QR-Code. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | Objek tipe HIBC LIC Aztec QR-Code. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | Objek tipe HIBC PAS QR-Code. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | Objek tipe HIBC PAS Data Matrix QR-Code. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | Objek tipe HIBC PAS Aztec QR-Code. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Objek tipe Han Xin QR-Code. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | Objek tipe GS1 Han Xin QR-Code. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | Objek tipe RectMicroQR. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | Objek tipe MicroQR. |

### Contoh

```python
from groupdocs.signature.domain import QrCodeTypes

# Gunakan enumerasi tipe kode QR saat membuat opsi tanda tangan
print(QrCodeTypes.QR)
```

### Guides
Panduan tugas yang menggunakan `QrCodeTypes`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
