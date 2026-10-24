---
title: "Класс DigitalVBA"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет цифровую подпись для проектов VBA в электронных таблицах."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Представляет цифровую подпись для проектов VBA в электронных таблицах.

Обеспечивает возможность подписывать проект VBA в форматах электронных таблиц, таких как `Xlsm` или `Xltm`. Если несколько расширений [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) добавлены в [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), используется только первое при подписи.

Тип DigitalVBA раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Инициализирует новый экземпляр класса DigitalVBA с файлом сертификата. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Инициализирует новый экземпляр класса DigitalVBA с потоком сертификата. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Получает копию этого объекта. (унаследовано от [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Путь к файлу цифрового сертификата, используется только если `CertificateStream` не указан. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | Поток цифрового сертификата. Если это свойство указано, оно всегда используется вместо CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | Комментарии подписи. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | Пароль цифрового сертификата. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | Настройка, определяющая, подписывается ли только проект VBA. Когда True, сам документ таблицы не подписывается; подписывается только проект VBA. |

### Пример

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Подписать макросы в таблице
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Добавить расширение для цифровой подписи проекта VBA
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Проверить, что часть подписи проекта VBA была добавлена
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### См. также
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
