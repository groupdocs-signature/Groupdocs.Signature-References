---
title: "Класс DigitalVerifyOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Содержит параметры для проверки цифровой подписи документа."
type: docs
url: /ru/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Содержит параметры для проверки цифровой подписи документа.

Узнать больше

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

Тип DigitalVerifyOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Инициализирует экземпляр DigitalVerifyOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Инициализирует экземпляр DigitalVerifyOptions с указанным путем к файлу цифрового сертификата. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Инициализирует экземпляр DigitalVerifyOptions с указанным потоком сертификата. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | Сертификат X509Certificate2, полученный из пути к файлу сертификата или потока. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Путь к файлу цифрового сертификата. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | Поток цифрового сертификата. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | Комментарии цифровой подписи для проверки. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Контакт подписи для проверки. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | Имя издателя сертификата для проверки. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | Местоположение подписи для проверки. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | Пароль цифрового сертификата, если требуется. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | Причина цифровой подписи для проверки. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | Начало диапазона даты и времени цифровой подписи для проверки. Значение None будет игнорировано. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | Конец диапазона даты и времени цифровой подписи для проверки. Значение null будет игнорировано. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | Отличительное имя субъекта сертификата для проверки; проверка подтверждает, содержит ли имя субъекта подписи или равно этому чувствительному к регистру значению. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Флаг, указывающий, должна ли проверяться каждая страница документа. По умолчанию значение True. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Дополнительные расширения для проверки альтернативных параметров подписи. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Флаг свойства valid. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Номер страницы документа, подлежащей проверке; если не задан, проверяются все страницы документа при первом вхождении (минимальное значение 1). (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Параметры страниц для указания страниц, подлежащих проверке. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Позиция фигуры в макете документа, используемая для проверки подписей в заголовках/колонтитулах. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
