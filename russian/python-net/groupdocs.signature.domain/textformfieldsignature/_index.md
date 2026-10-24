---
title: "Класс TextFormFieldSignature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет свойства подписи текстового поля формы ввода для PDF‑документов."
type: docs
url: /ru/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

Представляет свойства подписи текстового поля формы ввода для PDF‑документов.

Тип TextFormFieldSignature раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | Инициализирует PdfTextFormFieldSignature с предопределённым именем. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | Инициализирует PdfTextFormFieldSignature с предопределённым именем. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | Создайте копию экземпляра подписи FormField. |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | Сравнивает эту подпись с другой подписью на равенство по типу и значениям свойств. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | Переопределяет метод GetHashCode. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | Текст ввода поля формы. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Дата создания подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Флаг, указывающий, была ли эта подпись удалена из документа. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Высота подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Флаг, указывающий, представляет ли этот компонент подпись (`True`) или содержимое документа (`False`). (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Левая позиция подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Дата изменения подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | Уникальное имя поля формы. (унаследовано от [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Номер страницы, на которой была найдена подпись. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Уникальный идентификатор подписи, используемый для изменения подписи в документе через операции обновления или удаления. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Тип подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Верхняя позиция подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | Тип поля формы. (унаследовано от [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | Объект данных поля формы. (унаследовано от [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Ширина подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # Создайте текстовое поле формы с именем "FieldText" и значением "Value1"
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # Создайте параметры поля формы для него
        options = FormFieldSignOptions(text_field)

        # Установите положение и размер поля формы
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # Подпишите документ и сохраните результат
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
