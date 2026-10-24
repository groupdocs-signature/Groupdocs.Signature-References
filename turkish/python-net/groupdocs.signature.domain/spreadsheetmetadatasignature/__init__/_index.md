---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Önceden tanımlı ad ve boş değerle Spreadsheet Metadata Signature'ı başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Önceden tanımlı ad ve boş değerle Spreadsheet Metadata Signature'ı başlatır.

```python
def __init__(self, name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Spreadsheet Metadata Signature adı. |

## __init__ {#name-value}

Önceden tanımlı değerlerle bir Spreadsheet Metadata Signature başlatır.

```python
def __init__(self, name, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Meta veri imza nesnesinin adı. |
| value | `Any` | Meta veri imzasının değeri. |

### Örnek

```python
from datetime import datetime
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Bir elektronik tablo için meta veri imzaları oluşturun
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Ayrıca Bakınız
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
