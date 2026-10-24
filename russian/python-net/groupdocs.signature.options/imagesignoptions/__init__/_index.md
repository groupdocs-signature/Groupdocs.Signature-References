---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса ImageSignOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса ImageSignOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature.options import ImageSignOptions

# Создайте параметры подписи изображения, используя путь к файлу изображения
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Инициализирует ImageSignOptions файлом изображения.

```python
def __init__(self, image_file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_file_path | `str` | Путь к файлу изображения. |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # Настройте дополнительные параметры здесь, например, позицию, размер и т.д.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Инициализирует новый экземпляр ImageSignOptions потоком изображения.

```python
def __init__(self, image_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Поток изображения. |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### См. также
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
