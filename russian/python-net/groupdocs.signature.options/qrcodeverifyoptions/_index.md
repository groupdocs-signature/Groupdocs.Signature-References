---
title: "Класс QrCodeVerifyOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Содержит параметры для проверки подписи QR‑кода документа."
type: docs
url: /ru/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

Содержит параметры для проверки подписи QR‑кода документа.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

Тип QrCodeVerifyOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | Инициализирует параметры проверки для подписей QR-Code. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | Инициализирует параметры проверки для подписей QR-Code с указанным текстом QR-кода. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | Инициализирует параметры проверки для подписей QR-Code с текстом и типом кодирования QR-Code для проверки. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | Реализация [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) используется для кодирования и декодирования текстовых свойств подписи QR-Code. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | Проверка типа QR-code. Это свойство является необязательным. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Флаг, указывающий, должна ли проверяться каждая страница документа. По умолчанию значение True. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Дополнительные расширения для проверки альтернативных параметров подписи. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Заголовок поля формы для проверки. Если задан, текст будет найден только в текстовых полях формы. (наследовано от [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Тип поля формы для проверки; если задан, текст будет найден только в текстовых полях формы. (наследовано от [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Флаг свойства valid. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Проверка типа совпадения текста. (наследовано от [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Номер страницы документа, подлежащей проверке; если не задан, проверяются все страницы документа при первом вхождении (минимальное значение 1). (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Параметры страниц для указания страниц, подлежащих проверке. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Позиция фигуры в макете документа, используемая для проверки подписей в заголовках/колонтитулах. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | Идентификатор текстовой подписи для проверки. Должен быть больше нуля; поддерживается только для PDF‑документов. (наследовано от [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Тип подписи, подлежащей проверке. (наследовано от [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Текст подписи для проверки. (наследовано от [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
