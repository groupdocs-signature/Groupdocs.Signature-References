---
title: "Класс SearchResult"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет результат поиска подписей в указанном документе."
type: docs
url: /ru/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Представляет результат поиска подписей в указанном документе.

Тип SearchResult раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Возвращает итератор по результатам поиска. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | Размер целевого документа, который всегда равен 0 для метода Search. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | Список подписей [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/), которые не прошли процесс поиска по критериям. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | Время выполнения процесса поиска в миллисекундах. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | Список найденных подписей [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | Размер исходного документа. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | Список найденных подписей ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Общее количество обработанных подписей, возвращённых процессом поиска. |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
