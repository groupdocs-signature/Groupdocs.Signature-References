---
title: "Метод sign"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Подписывает документ с помощью SignOptions и сохраняет результат в поток."
type: docs
url: /ru/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Подписывает документ с помощью [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат в поток.

```python
def sign(self, document, sign_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток выходного документа. |
| sign_options | `SignOptions` | Параметры подписи. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Примечания:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#document-sign_options-save_options}

Подписывает документ с помощью [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат в поток, используя предопределённые [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Узнать больше
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток выходного документа. |
| sign_options | `SignOptions` | Параметры подписи. |
| save_options | `SaveOptions` | Параметры сохранения. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Подписывает документ набором [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат в поток.

Узнать больше

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток выходного документа. |
| sign_options_list | `List[SignOptions]` | Список параметров подписи. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Подписывает документ набором [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат в поток, используя предопределённые [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток выходного документа. |
| sign_options_list | `List[SignOptions]` | Список параметров подписи. |
| save_options | `SaveOptions` | Параметры сохранения. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Примечания:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Подпишите и сохраните результат в новый файл; исходный файл останется без изменений
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Подписывает документ с помощью SignOptions и сохраняет результат по указанному пути к файлу.

Узнать больше

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к выходному файлу. |
| sign_options | `SignOptions` | Параметры подписи. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options-save_options}

Подписывает документ с помощью [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат по указанному пути к файлу, используя предопределённые [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к выходному файлу. |
| sign_options | `SignOptions` | Параметры подписи. |
| save_options | `SaveOptions` | Параметры сохранения. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Откройте документ; блок with освобождает файл, когда он заканчивается
    with Signature("sample.pdf") as signature:
        # Текстовая подпись, расположенная на 100 пикселей от левого и верхнего краев первой страницы
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Подпишите и сохраните результат в новый файл; исходный файл останется без изменений
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Подписывает документ набором [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат по указанному пути к файлу.

Узнать больше:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к выходному файлу. |
| sign_options_list | `List[SignOptions]` | Список параметров подписи. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    options.left = 100
    options.top = 100
    result = signature.sign("signed_sample.pdf", options)
    print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list-save_options}

Подписывает документ набором [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат по указанному пути к файлу, используя предопределённые [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Узнать больше:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к выходному файлу. |
| sign_options_list | `List[SignOptions]` | Список параметров подписи. |
| save_options | `SaveOptions` | Параметры сохранения. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### См. также
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
