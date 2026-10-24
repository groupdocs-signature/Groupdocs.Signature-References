---
title: "Класс QrCodeSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры поиска для подписей QR‑кода."
type: docs
url: /ru/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

Представляет параметры поиска для подписей QR‑кода.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

Тип QrCodeSearchOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | Инициализирует новый экземпляр класса QRCodeSearchOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | Инициализирует новый экземпляр класса QRCodeSearchOptions со значением типа кодирования. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | Инициализирует новый экземпляр класса QRCodeSearchOptions с типом кодирования и значениями текста. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | Реализация [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) используется для кодирования и декодирования текста подписи QR‑Code или свойств данных. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | Тип кодирования для поиска QR‑кодов. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | Тип сопоставления текста QR‑Code, используемый при поиске. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | Флаг, определяющий, возвращается ли изображение QR‑Code для каждой подписи на странице документа. Когда установлен в True, необработанные данные изображения сохраняются в свойстве подписи `content` в формате, указанном параметром `return_content_type`. По умолчанию отключено. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | Тип файла возвращаемого содержимого изображения подписи QR‑Code, когда включено свойство `return_content`. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | Текст подписи QR‑Code для поиска и сопоставления. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Флаг, указывающий, выполнять ли поиск на каждой странице документа. По умолчанию значение равно True. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Номер страницы документа для поиска (необязательно). (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Параметры для указания страниц при поиске подписи. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Флаг, указывающий, возвращать ли позицию формы в макете документа. Доступно только для документов Word. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Флаг для возврата только подписей, помеченных как `IsSignature`. По умолчанию значение `False`, что означает, что возвращаются все подписи, соответствующие указанным критериям. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
