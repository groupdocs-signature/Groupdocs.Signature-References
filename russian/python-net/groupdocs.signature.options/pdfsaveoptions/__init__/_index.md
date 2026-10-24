---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр PdfSaveOptions со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр PdfSaveOptions со значениями по умолчанию.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Инициализирует новый экземпляр PdfSaveOptions с указанным форматом выходного файла.

```python
def __init__(self, file_format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Тип выходного файла `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Инициализирует новый экземпляр PdfSaveOptions с флагом перезаписи.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Флаг, указывающий, следует ли перезаписывать подписанный файл тем же файлом. |

## __init__ {#file_format-overwrite_existing_file}

Инициализирует новый экземпляр PdfSaveOptions с указанным форматом выходного файла и флагом перезаписи.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Тип выходного файла. |
| overwrite_existing_file | `bool` | Флаг, указывающий, следует ли перезаписывать подписанный файл тем же файлом. |

### Пример

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Создайте параметры сохранения с форматом PDF и разрешите перезапись существующих файлов
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### См. также
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
