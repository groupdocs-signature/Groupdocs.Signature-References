---
title: "Класс BarcodeVerifyOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры проверки штрих-кода."
type: docs
url: /ru/python-net/groupdocs.signature.options/barcodeverifyoptions/
is_root: false
weight: 30
---


## BarcodeVerifyOptions class

Представляет параметры проверки штрих-кода.

Узнать больше
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings

Тип BarcodeVerifyOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/) | Инициализирует параметр проверки по умолчанию для подписи штрихкода. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text) | Инициализирует параметр проверки по умолчанию с текстом проверки. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#encode_type) | Инициализирует параметр проверки по умолчанию с проверкой типа штрихкода. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text-encode_type) | Инициализирует параметр проверки по умолчанию с проверкой типа штрих‑кода и текста. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/encode_type/) | Тип штрих‑кода, используемый для проверки. |
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
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import BarcodeVerifyOptions


def verify_barcode_signatures():
    with Signature("signed.pdf") as signature:
        options = BarcodeVerifyOptions()
        options.all_pages = True
        options.text = "12345"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document was verified successfully: {len(result.succeeded)} matching barcode signature(s).")
        else:
            print("Document failed verification process.")
```

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
