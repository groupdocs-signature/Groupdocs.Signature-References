---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Önceden tanımlı bir ad ve boş bir değerle bir PDF meta veri imzası başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Önceden tanımlı bir ad ve boş bir değerle bir PDF meta veri imzası başlatır.

```python
def __init__(self, name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | PDF meta veri imza adı. |

## __init__ {#name-value}

Önceden tanımlı değerlerle bir PDF meta veri imzası başlatır.

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
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

Önceden tanımlı değerlerle bir PDF meta veri imzası başlatır.

```python
def __init__(self, name, value, tag):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Meta veri imza nesnesinin adı. |
| value | `Any` | Meta veri imzasının değeri. |
| tag | `str` | Meta veri imzasının ön ek etiketi. |

### Örnek

```python
from groupdocs.signature.domain import PdfMetadataSignature

# PDF yazarının meta veri imzasını oluştur
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Oluşturma tarihi için meta veri imzası oluştur
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Sayısal tanımlayıcı için meta veri imzası oluştur
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Kayan nokta değeri için meta veri imzası oluştur
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Ayrıca Bakınız
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
