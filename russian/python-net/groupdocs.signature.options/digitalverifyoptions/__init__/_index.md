---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует экземпляр DigitalVerifyOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует экземпляр DigitalVerifyOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

Инициализирует экземпляр DigitalVerifyOptions с указанным путем к файлу цифрового сертификата.

```python
def __init__(self, certificate_file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_file_path | `str` | Путь к файлу цифрового сертификата. |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Инициализирует экземпляр DigitalVerifyOptions с указанным потоком сертификата.

```python
def __init__(self, certificate_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Поток сертификата. |

### См. также
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
