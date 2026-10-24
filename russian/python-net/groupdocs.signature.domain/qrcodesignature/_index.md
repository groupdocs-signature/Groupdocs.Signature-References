---
title: "Класс QrCodeSignature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет свойства подписи QR-кода."
type: docs
url: /ru/python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 550
---


## QrCodeSignature class

Представляет свойства подписи QR-кода.

Тип QrCodeSignature раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#signature_id) | Инициализирует объект QrCodeSignature с идентификатором подписи, полученным после процесса поиска. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/) | Клонирует экземпляр QR-Code Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals/#obj) | Определяет, равен ли данный объект подписи этому экземпляру. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_hash_code/) | Переопределяет метод GetHashCode. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content/) | Бинарное изображение данных QR-кода типа [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type/) | Тип кодирования QR-кода. |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) | Формат изображения подписи QR-кода. |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text/) | Текст QR-кода. |
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
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    if result.signatures:
        qr = result.signatures[0]
        print(qr.text, qr.encode_type.type_name, qr.left, qr.top)
```

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
