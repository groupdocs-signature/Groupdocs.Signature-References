---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса SpreadsheetSaveOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/spreadsheetsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса SpreadsheetSaveOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Инициализирует новый экземпляр SpreadsheetSaveOptions с предопределённым форматом выходного файла.

```python
def __init__(self, file_format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_format | `SpreadsheetSaveFileFormat` | Указывает формат выходного файла. |

## __init__ {#file_format-overwrite_existing_file}

Инициализирует новый экземпляр SpreadsheetSaveOptions с указанным форматом выходного файла и флагом перезаписи.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_format | `SpreadsheetSaveFileFormat` | Указывает формат выходного файла. |
| overwrite_existing_file | `bool` | Флаг, указывающий, следует ли перезаписывать подписанный файл тем же файлом. |

### См. также
* class [`SpreadsheetSaveOptions`](/signature/python-net/groupdocs.signature.options/spreadsheetsaveoptions/)
