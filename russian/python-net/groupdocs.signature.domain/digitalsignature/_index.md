---
title: "Класс DigitalSignature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Класс содержит свойства цифровой подписи."
type: docs
url: /ru/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

Класс содержит свойства цифровой подписи.

Тип DigitalSignature предоставляет следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | Инициализирует цифровую подпись с параметрами по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | Инициализирует цифровую подпись с известным идентификатором подписи. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | Инициализирует DigitalSignature, используя первый сертификат из указанного хранилища X509. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | Инициализирует DigitalSignature на основе указанного хранилища X509 и индекса сертификата. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | Инициализирует цифровую подпись с указанным сертификатом. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | Клонирует экземпляр подписи штрих‑кода. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | Сравнивает эту подпись с другой подписью на равенство. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | Возвращает хеш‑код цифровой подписи. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Загружает цифровые подписи из всех системных хранилищ сертификатов X509. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Загружает цифровые подписи из хранилища сертификатов. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Загружает цифровые подписи из хранилища сертификатов. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Загружает цифровые подписи из хранилища цифровых сертификатов, расположенного в определённом месте. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Загружает цифровые подписи из хранилища цифровых сертификатов, размещённого в определённом месте. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Сертификат X509, связанный с цифровой подписью. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Пользовательское имя хранилища сертификата. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Расположение хранилища сертификата. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Имя хранилища сертификата. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Комментарий о цели подписи. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Цифровая подпись действительна, и документ не был изменён. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Время подписи документа. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Отпечаток сертификата. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Тип XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
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
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
