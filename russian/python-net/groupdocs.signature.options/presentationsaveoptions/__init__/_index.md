---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр PresentationSaveOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/presentationsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр PresentationSaveOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Инициализирует новый экземпляр PresentationSaveOptions с указанным форматом выходного файла.

```python
def __init__(self, file_format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_format | `PresentationSaveFileFormat` | Тип выходного файла. |

## __init__ {#overwrite_existing_file}

Инициализирует новый экземпляр PresentationSaveOptions с указанным типом вывода и флагом перезаписи.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Флаг, указывающий, следует ли перезаписывать подписанный файл тем же файлом. |

## __init__ {#file_format-overwrite_existing_file}

Инициализирует новый экземпляр PresentationSaveOptions с указанным форматом выходного файла и флагом перезаписи.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_format | `PresentationSaveFileFormat` | Тип выходного файла `PresentationSaveFileFormat`. |
| overwrite_existing_file | `bool` | Флаг, указывающий, следует ли перезаписать существующий подписанный файл. |

### См. также
* class [`PresentationSaveOptions`](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/)
