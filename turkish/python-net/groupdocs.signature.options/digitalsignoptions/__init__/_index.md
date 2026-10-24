---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "DigitalSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

DigitalSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Yeni bir DigitalSignOptions örneğini bir sertifika dosyasıyla başlatır.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_file_path | `str` | Dijital sertifika dosya yolu. |

### Örnek

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream}

Yeni bir DigitalSignOptions örneğini bir sertifika akışıyla başlatır.

```python
def __init__(self, certificate_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Dijital Sertifika akışı. |

### Örnek

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with open("certificate.pfx", "rb") as cert_stream:
        options = DigitalSignOptions(cert_stream)
        options.password = "1234567890"

        with Signature("sample.pdf") as signature:
            result = signature.sign("signed.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_file_path-image_file_path}

DigitalSignOptions sınıfının yeni bir örneğini bir sertifika dosyası ve bir görünüm görüntü dosyasıyla başlatır.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_file_path | `str` | Dijital sertifika dosya yolu. |
| image_file_path | `str` | İmza görünümü resim dosya yolu. |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Sertifikayı ve görünüm görselini yapıcıya geçirin
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

DigitalSignOptions'ın yeni bir örneğini bir sertifika dosyası ve bir görünüm görüntü akışıyla başlatır.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_file_path | `str` | Dijital sertifika dosya yolu. |
| appearence_image_stream | `io.RawIOBase` | İmza görünümü resim akışı. |

### Örnek

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream-image_file_path}

DigitalSignOptions'ın yeni bir örneğini bir sertifika akışı ve bir görünüm görüntü dosyasıyla başlatır.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Dijital Sertifika akışı. |
| image_file_path | `str` | str. İmza Görünümü resim dosya yolu. |

## __init__ {#certificate_stream-appearence_image_stream}

Yeni bir DigitalSignOptions örneğini bir sertifika akışı ve bir görünüm görüntü akışıyla başlatır.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Dijital Sertifika akışı. |
| appearence_image_stream | `io.RawIOBase` | İmza görünümü resim akışı. |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Sertifikayı ve görünüm resmini akışlardan yükle
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Ayrıca Bakınız
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
