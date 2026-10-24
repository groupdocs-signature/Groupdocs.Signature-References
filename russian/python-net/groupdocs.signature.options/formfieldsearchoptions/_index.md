---
title: "Класс FormFieldSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры поиска для подписей полей формы."
type: docs
url: /ru/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Представляет параметры поиска для подписей полей формы.

Узнать больше:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

Тип FormFieldSearchOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Инициализирует новый экземпляр класса FormFieldSearchOptions со значениями по умолчанию. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | Шаблон регулярного выражения, используемый для сопоставления имени подписи поля формы во время поиска. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | Тип подписи поля формы для поиска. Значение по умолчанию — None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | Значение подписи поля формы для поиска. По умолчанию — None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Флаг, указывающий, выполнять ли поиск на каждой странице документа. По умолчанию значение равно True. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Номер страницы документа для поиска (необязательно). (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Параметры для указания страниц при поиске подписи. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Флаг, указывающий, возвращать ли позицию формы в макете документа. Доступно только для документов Word. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Флаг для возврата только подписей, помеченных как `IsSignature`. По умолчанию значение `False`, что означает, что возвращаются все подписи, соответствующие указанным критериям. (унаследовано от [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Возвращать только текстовые поля с именем "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
