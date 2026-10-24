---
title: "Класс DigitalSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры поиска для цифровых подписей."
type: docs
url: /ru/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

Представляет параметры поиска для цифровых подписей.

Узнать больше

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

Тип DigitalSearchOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | Инициализирует новый экземпляр класса DigitalSearchOptions со значениями по умолчанию. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | Комментарии к цифровой подписи для поиска. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | Уникальное имя издателя сертификата для поиска, когда значение не пусто. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | Диапазон даты и времени цифровой подписи для поиска. Nullable‑значение будет игнорироваться. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | Конец диапазона даты и времени цифровых подписей для поиска. Значение null будет игнорироваться. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | Уникальное имя субъекта сертификата для поиска, когда предоставлено непустое значение. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Флаг, указывающий, выполнять ли поиск на каждой странице документа. По умолчанию значение равно True. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Номер страницы документа для поиска (необязательно). (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Параметры для указания страниц при поиске подписи. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Флаг, указывающий, возвращать ли позицию формы в макете документа. Доступно только для документов Word. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Флаг для возврата только подписей, помеченных как `IsSignature`. По умолчанию значение `False`, что означает, что возвращаются все подписи, соответствующие указанным критериям. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
