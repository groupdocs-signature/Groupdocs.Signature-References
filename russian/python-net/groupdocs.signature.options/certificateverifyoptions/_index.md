---
title: "Класс CertificateVerifyOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Содержит параметры для проверки сертификатных документов."
type: docs
url: /ru/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Содержит параметры для проверки сертификатных документов.

Узнать больше

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

Тип CertificateVerifyOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Инициализирует новый экземпляр TextVerifyOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Инициализирует новый экземпляр CertificateVerifyOptions с субъектом для проверки. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | Свойство указывает, истёк ли сертификат на основе результата проверки. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | Издатель сертификата для проверки. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | Тип сопоставления текста, используемый для проверки. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | Процесс проверки должен обеспечивать проверку цепочки X.509 с использованием базовой политики проверки. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | Серийный номер сертификата для проверки. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | Субъект сертификата для проверки. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | Отпечаток сертификата для проверки. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Флаг, указывающий, должна ли проверяться каждая страница документа. По умолчанию значение True. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Дополнительные расширения для проверки альтернативных параметров подписи. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Флаг свойства valid. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Номер страницы документа, подлежащей проверке; если не задан, проверяются все страницы документа при первом вхождении (минимальное значение 1). (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Параметры страниц для указания страниц, подлежащих проверке. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Позиция фигуры в макете документа, используемая для проверки подписей в заголовках/колонтитулах. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
