---
title: "Класс BarcodeSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры поиска для подписей штрих-кода."
type: docs
url: /ru/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

Представляет параметры поиска для подписей штрих-кода.

Узнать больше:
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

Тип BarcodeSearchOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | Инициализирует новый экземпляр класса BarcodeSearchOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | Инициализирует новый экземпляр класса BarcodeSearchOptions со значением типа кодирования. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | Инициализирует новый экземпляр класса BarcodeSearchOptions со значениями типа кодирования и текста. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | Тип кодирования, используемый для фильтрации поиска штрихкодов; если не установлен, поиск включает все поддерживаемые типы штрихкодов. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | Тип сопоставления текста штрихкода, используемый для поиска. Он используется только когда свойство `text` установлено. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | Флаг, указывающий, следует ли получать изображение штрихкода подписи на странице документа. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | Тип файла возвращаемого содержимого изображения для подписи штрихкода, когда включено свойство `return_content`. |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | Текст подписи штрихкода для поиска и сопоставления. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Флаг, указывающий, выполнять ли поиск на каждой странице документа. По умолчанию значение равно True. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Номер страницы документа для поиска (необязательно). (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Параметры для указания страниц при поиске подписи. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Флаг, указывающий, возвращать ли позицию формы в макете документа. Доступно только для документов Word. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Флаг для возврата только подписей, помеченных как `IsSignature`. По умолчанию значение `False`, что означает, что возвращаются все подписи, соответствующие указанным критериям. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
Руководства задач, использующие `BarcodeSearchOptions`:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
