---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديدًا من PdfSaveOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثيلاً جديدًا من PdfSaveOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

يُنشئ مثيلاً جديدًا من PdfSaveOptions بالتنسيق المحدد لملف الإخراج.

```python
def __init__(self, file_format):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | نوع ملف الإخراج `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

يُنشئ مثيلاً جديدًا من PdfSaveOptions بعلم الكتابة فوق.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| overwrite_existing_file | `bool` | العلم ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |

## __init__ {#file_format-overwrite_existing_file}

يُنشئ مثيلاً جديدًا من PdfSaveOptions بالتنسيق المحدد لملف الإخراج وعلم الكتابة فوق.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | نوع ملف الإخراج. |
| overwrite_existing_file | `bool` | العلم ما إذا كان سيتم استبدال الملف الموقّع بنفس الملف. |

### مثال

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# إنشاء خيارات الحفظ بصيغة PDF والسماح بالكتابة فوق الملفات الموجودة
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### انظر أيضًا
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
