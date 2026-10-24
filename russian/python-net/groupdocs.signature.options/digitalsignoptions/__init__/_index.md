---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса DigitalSignOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса DigitalSignOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Инициализирует новый экземпляр DigitalSignOptions с файлом сертификата.

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
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream}

Инициализирует новый экземпляр DigitalSignOptions с потоком сертификата.

```python
def __init__(self, certificate_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Поток цифрового сертификата. |

### Пример

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with open("certificate.pfx", "rb") as cert_stream:
        options = DigitalSignOptions(cert_stream)
        options.password = "1234567890"

        with Signature("sample.pdf") as signature:
            result = signature.sign("signed.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_file_path-image_file_path}

Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и файлом изображения внешнего вида.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_file_path | `str` | Путь к файлу цифрового сертификата. |
| image_file_path | `str` | Путь к файлу изображения внешнего вида подписи. |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Передайте сертификат и изображение внешнего вида в конструктор
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Инициализирует новый экземпляр DigitalSignOptions с файлом сертификата и потоком изображения внешнего вида.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_file_path | `str` | Путь к файлу цифрового сертификата. |
| appearence_image_stream | `io.RawIOBase` | Поток изображения внешнего вида подписи. |

### Пример

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream-image_file_path}

Инициализирует новый экземпляр DigitalSignOptions с потоком сертификата и файлом изображения внешнего вида.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Поток цифрового сертификата. |
| image_file_path | `str` | str. Путь к файлу изображения внешнего вида подписи. |

## __init__ {#certificate_stream-appearence_image_stream}

Инициализирует новый экземпляр DigitalSignOptions с потоком сертификата и потоком изображения внешнего вида.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Поток цифрового сертификата. |
| appearence_image_stream | `io.RawIOBase` | Поток изображения внешнего вида подписи. |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Загрузить сертификат и изображение внешнего вида из потоков
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### См. также
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
