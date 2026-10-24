---
title: "Класс CertificateSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры поиска для подписей метаданных сертификата."
type: docs
url: /ru/python-net/groupdocs.signature.options/certificatesearchoptions/
is_root: false
weight: 60
---


## CertificateSearchOptions class

Представляет параметры поиска для подписей метаданных сертификата.

Узнать больше

- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: Advanced search within Digital Certificate X509 documents (https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

Тип CertificateSearchOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/) | Инициализирует новый экземпляр класса TextSearchOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/#text) | Инициализирует новый экземпляр класса TextSearchOptions со значением текста. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/match_type/) | Тип совпадения текста, используемый для поиска. |
| [text](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/text/) | Текст свойства сертификата для сопоставления при поиске. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Флаг, указывающий, выполнять ли поиск на каждой странице документа. По умолчанию значение равно True. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Номер страницы документа для поиска (необязательно). (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Параметры для указания страниц при поиске подписи. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Флаг, указывающий, возвращать ли позицию формы в макете документа. Доступно только для документов Word. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Флаг для возврата только подписей, помеченных как `IsSignature`. По умолчанию значение `False`, что означает, что возвращаются все подписи, соответствующие указанным критериям. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
