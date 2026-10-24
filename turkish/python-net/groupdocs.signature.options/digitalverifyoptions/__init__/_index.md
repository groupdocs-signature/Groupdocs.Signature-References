---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "DigitalVerifyOptions örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

DigitalVerifyOptions örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

DigitalVerifyOptions örneğini verilen dijital sertifika dosya yolu ile başlatır.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_file_path | `str` | Dijital sertifikanın dosya yolu. |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

DigitalVerifyOptions örneğini verilen sertifika akışı ile başlatır.

```python
def __init__(self, certificate_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Sertifikanın akışı. |

### Ayrıca Bakınız
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
