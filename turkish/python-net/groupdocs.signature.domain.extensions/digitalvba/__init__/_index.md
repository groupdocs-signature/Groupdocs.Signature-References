---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "DigitalVBA sınıfının yeni bir örneğini bir sertifika dosyasıyla başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

DigitalVBA sınıfının yeni bir örneğini bir sertifika dosyasıyla başlatır.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_file_path | `str` | Dijital sertifika dosya yolu. |
| password | `str` | Dijital sertifika şifresi. |

### Örnek

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Bir sertifika dosyası ve şifre kullanarak DigitalVBA uzantısı oluşturun
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

DigitalVBA sınıfının yeni bir örneğini bir sertifika akışıyla başlatır.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Dijital sertifikayı içeren io.RawIOBase |
| password | `str` | Dijital sertifika için str şifre. |

### Ayrıca Bakınız
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
