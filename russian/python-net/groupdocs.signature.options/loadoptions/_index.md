---
title: "Класс LoadOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Класс LoadOptions позволяет указывать дополнительные параметры (например, пароль) при открытии документа для подписи."
type: docs
url: /ru/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

Класс LoadOptions позволяет указывать дополнительные параметры (например, пароль) при открытии документа для подписи.

Установите атрибут `password` в пароль документа, если файл зашифрован.

Тип LoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Инициализирует новый экземпляр класса LoadOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Инициализирует новый экземпляр класса [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) с указанным типом файла. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Тип файла, связанный с параметрами загрузки, по умолчанию [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | Флаг, определяющий, загружает ли документ внешние ресурсы. Это свойство устарело; вместо него используйте [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), которое имеет противоположное значение. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | Пароль, используемый для открытия защищённого документа и для сохранения подписанного документа как защищённого. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | Разрешения PDF‑документа, такие как печать, изменение и извлечение данных. Только для PDF‑документов. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | Флаг, который останавливает загрузку внешних ресурсов документом. Значение по умолчанию — True; внешние ресурсы не загружаются, за исключением тех, которые соответствуют [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | Список фрагментов адресов внешних ресурсов, которые загружаются даже когда [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) установлен в true. Значение по умолчанию — пустой список. |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
