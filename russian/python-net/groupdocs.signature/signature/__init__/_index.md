---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр Signature с документом, предоставленным в виде потока."
type: docs
url: /ru/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Инициализирует новый экземпляр Signature с документом, предоставленным в виде потока.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток содержимого документа. |

## __init__ {#document-load_options}

Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с потоком документа и параметрами загрузки.

Узнать больше

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток содержимого документа. |
| load_options | `LoadOptions` | Параметры загрузки документа. |

## __init__ {#document-settings}

Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с документом, предоставленным через поток, и необязательными [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Узнать больше:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток содержимого документа. |
| settings | `SignatureSettings` | Настройки подписи. |

## __init__ {#document-load_options-settings}

Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с потоком документа, параметрами загрузки и настройками подписи.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document | `io.RawIOBase` | Поток содержимого документа. |
| load_options | `LoadOptions` | Параметры загрузки документа. |
| settings | `SignatureSettings` | Настройки подписи. |

## __init__ {#file_path}

Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с документом, предоставленным по пути к файлу.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Абсолютный или относительный путь к файлу. |

### Пример

```python
from groupdocs.signature import Signature

# Откройте документ для подписи, поиска или проверки
with Signature("sample.pdf") as signature:
    # работайте с объектом подписи
    pass
```

## __init__ {#file_path-load_options}

Инициализирует новый экземпляр Signature с документом, предоставленным по пути к файлу, и параметрами загрузки.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Абсолютный или относительный путь к файлу. |
| load_options | `LoadOptions` | Параметры загрузки документа. |

### Пример

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Выполняйте операции подписи, поиска или проверки
    pass
```

## __init__ {#file_path-settings}

Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с документом, предоставленным по пути к файлу, и необязательными [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Абсолютный или относительный путь к файлу. |
| settings | `SignatureSettings` | Настройки подписи. |

### Пример

```python
from groupdocs.signature import Signature

# Откройте PDF‑документ для подписи или проверки
with Signature("sample.pdf") as signature:
    # Используйте здесь экземпляр подписи (например, sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с документом, предоставленным по пути к файлу, параметрами загрузки и настройками подписи.

Узнать больше:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Абсолютный или относительный путь к файлу. |
| load_options | `LoadOptions` | Параметры загрузки документа. |
| settings | `SignatureSettings` | Настройки подписи. |

### Пример

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # выполнять операции подписи, проверки или поиска
    pass
```

### См. также
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
