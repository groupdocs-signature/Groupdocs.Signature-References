---
title: "Класс TextSignature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Класс TextSignature содержит свойства текстовой подписи."
type: docs
url: /ru/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

Класс TextSignature содержит свойства текстовой подписи.

Тип TextSignature раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | Инициализирует объект TextSignature с уникальным идентификатором подписи, полученным в результате операции подписи или поиска. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Клонирует экземпляр Text Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Сравнивает указанную подпись с этим экземпляром на равенство. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | Возвращает хеш-код подписи. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | Встроенный атрибут, указывающий, является ли подпись специфичной для документа. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | Реализация текстовой подписи. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | Текст подписи. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Дата создания подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Флаг, указывающий, была ли эта подпись удалена из документа. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Высота подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Флаг, указывающий, представляет ли этот компонент подпись (`True`) или содержимое документа (`False`). (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Левая позиция подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Дата изменения подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Номер страницы, на которой была найдена подпись. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Уникальный идентификатор подписи, используемый для изменения подписи в документе через операции обновления или удаления. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Тип подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Верхняя позиция подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Ширина подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
