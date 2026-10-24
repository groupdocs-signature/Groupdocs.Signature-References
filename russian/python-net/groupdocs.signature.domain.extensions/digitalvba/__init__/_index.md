---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса DigitalVBA с файлом сертификата."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Инициализирует новый экземпляр класса DigitalVBA с файлом сертификата.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_file_path | `str` | Путь к файлу цифрового сертификата. |
| password | `str` | Пароль цифрового сертификата. |

### Пример

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Создать расширение DigitalVBA, используя файл сертификата и пароль
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Инициализирует новый экземпляр класса DigitalVBA с потоком сертификата.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase, содержащий цифровой сертификат. |
| password | `str` | str пароль для цифрового сертификата. |

### См. также
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
