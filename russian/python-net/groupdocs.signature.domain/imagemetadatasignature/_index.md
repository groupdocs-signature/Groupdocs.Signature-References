---
title: "Класс ImageMetadataSignature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет подпись метаданных изображения."
type: docs
url: /ru/python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 320
---


## ImageMetadataSignature class

Представляет подпись метаданных изображения.

Подписи метаданных для изображений являются электронными подписями, основанными на стандартах метаданных изображений, таких как EXIF. Каждая подпись идентифицируется числовым идентификатором (0‑65535) и хранит значение различных типов (текст, дата/время, целое, число с плавающей точкой).

Тип ImageMetadataSignature раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#id-value) | Инициализирует подпись метаданных изображения с указанным идентификатором и значением. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/) | Клонировать экземпляр подписи метаданных. |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#value) | Клонирует экземпляр ImageMetadataSignature с заданным значением. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals/#obj) | Определяет, равен ли указанный объект подписи этому экземпляру. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/get_hash_code/) | Возвращает хеш-код подписи. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/) | Преобразует значение подписи метаданных в логическое значение. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/) | Преобразует значение подписи метаданных в `datetime.datetime`. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#provider) | Преобразует значение подписи метаданных в `datetime`. |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/) | Преобразует в Decimal. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#provider) | Преобразует значение подписи метаданных в десятичное число. |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/) | Преобразует в float. |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#provider) | Преобразует значение подписи метаданных в тип float. |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/) | Преобразует значение подписи метаданных в целое число. |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/) | Преобразует в long. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/) | Преобразует в тип float. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#provider) | Преобразует значение подписи метаданных в тип float. |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/) | Преобразует значение подписи метаданных в строку. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format) | Преобразует значение подписи метаданных в строку, используя указанный формат. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format-provider) | Преобразует в строку с указанным форматом. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_string/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (унаследовано от [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (унаследовано от [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description/) | Описание стандартной подписи Image Metadata. |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id/) | Идентификатор подписи Image Metadata. См. класс `GroupDocs.Signature.Domain.ImageMetadataSignatures`, который содержит стандартную подпись с предопределённым значением Id. |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size/) | Размер значения метаданных. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Дата создания подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | Реализация [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) используется для кодирования и декодирования свойств значения подписи. (унаследовано от [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Флаг, указывающий, была ли эта подпись удалена из документа. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Высота подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Флаг, указывающий, представляет ли этот компонент подпись (`True`) или содержимое документа (`False`). (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Левая позиция подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Дата изменения подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | Уникальное имя метаданных. (унаследовано от [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Номер страницы, на которой была найдена подпись. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Уникальный идентификатор подписи, используемый для изменения подписи в документе через операции обновления или удаления. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Тип подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Верхняя позиция подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | Тип значения метаданных. (унаследовано от [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | Объект метаданных. (унаследовано от [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Ширина подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Пример

```python
from datetime import datetime

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature


def sign_png():
    with Signature("sample.png") as signature:
        options = MetadataSignOptions()

        metadata_id = 41996
        options.add(ImageMetadataSignature(metadata_id, "Mr.Scherlock Holmes"))   # text
        options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
        options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # whole number
        options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # floating‑point number

        result = signature.sign("signed.png", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.id}")
```

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
