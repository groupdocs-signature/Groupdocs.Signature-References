---
title: "Класс QrCodeTypes"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Контейнер типов QR-кода."
type: docs
url: /ru/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

Контейнер типов QR-кода.

Тип QrCodeTypes раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | Разбирает имя типа QR‑кода и возвращает соответствующий экземпляр QRCodeType. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | Возвращает тип QRCode, соответствующий указанному имени типа разбора, или None, если имя неизвестно. |

### Поля
| Поле | Описание |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | Все типы QRCode. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Объект типа Aztec QR‑Code. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | Объект типа DataMatrix QR‑Code. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | Объект типа QR QR‑Code. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | Объект типа GS1 DataMatrix QR‑Code. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | Объект типа GS1 QR‑Code. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | Объект типа HIBC LIC QR‑Code. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | Объект типа HIBC LIC Data Matrix QR‑Code. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | Объект типа HIBC LIC Aztec QR‑Code. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | Объект типа HIBC PAS QR‑Code. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | Объект типа HIBC PAS Data Matrix QR‑Code. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | Объект типа HIBC PAS Aztec QR‑Code. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Объект типа Han Xin QR‑Code. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | Объект типа GS1 Han Xin QR‑Code. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | Объект типа RectMicroQR. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | Объект типа MicroQR. |

### Пример

```python
from groupdocs.signature.domain import QrCodeTypes

# Используйте перечисление типов QR‑кода при создании параметров подписи
print(QrCodeTypes.QR)
```

### Guides
Руководства задач, использующие `QrCodeTypes`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
