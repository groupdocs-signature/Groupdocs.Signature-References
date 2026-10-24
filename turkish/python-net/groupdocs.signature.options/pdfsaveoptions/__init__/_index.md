---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "PdfSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

PdfSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya biçimiyle başlatır.

```python
def __init__(self, file_format):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Çıktı dosya türü `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

PdfSaveOptions sınıfının yeni bir örneğini üzerine yazma bayrağıyla başlatır.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Aynı dosyayla imzalı dosyanın üzerine yazılıp yazılmayacağını belirten bayrak. |

## __init__ {#file_format-overwrite_existing_file}

PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya biçimi ve üzerine yazma bayrağıyla başlatır.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Çıktı dosya türü. |
| overwrite_existing_file | `bool` | Aynı dosyayla imzalı dosyanın üzerine yazılıp yazılmayacağını belirten bayrak. |

### Örnek

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# PDF formatı ile kaydetme seçenekleri oluşturun ve mevcut dosyaların üzerine yazılmasına izin verin
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### Ayrıca Bakınız
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
