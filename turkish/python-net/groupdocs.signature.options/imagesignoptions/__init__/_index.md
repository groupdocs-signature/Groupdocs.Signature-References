---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "ImageSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

ImageSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature.options import ImageSignOptions

# Bir görüntü dosya yolu kullanarak görüntü imza seçenekleri oluşturun
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

ImageSignOptions'ı bir görüntü dosyasıyla başlatır.

```python
def __init__(self, image_file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_file_path | `str` | Görüntü dosyası yolu. |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # Burada ek seçenekleri yapılandırın, ör. konum, boyut, vb.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

ImageSignOptions'ın yeni bir örneğini bir görüntü akışıyla başlatır.

```python
def __init__(self, image_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Görüntü akışı. |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Ayrıca Bakınız
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
