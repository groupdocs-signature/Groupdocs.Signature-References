---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلاً جديداً من فئة DigitalSignOptions بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديداً من فئة DigitalSignOptions بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

ينشئ مثيلاً جديداً من DigitalSignOptions بملف شهادة.

```python
def __init__(self, certificate_file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_file_path | `str` | مسار ملف الشهادة الرقمية. |

### مثال

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

ينشئ مثيلاً جديداً من DigitalSignOptions بتدفق شهادة.

```python
def __init__(self, certificate_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | دفق الشهادة الرقمية. |

### مثال

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

ينشئ مثيلاً جديداً من فئة DigitalSignOptions بملف شهادة وملف صورة مظهر.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_file_path | `str` | مسار ملف الشهادة الرقمية. |
| image_file_path | `str` | مسار ملف صورة مظهر التوقيع. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # مرّر الشهادة وصورة المظهر إلى المُنشئ
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

ينشئ مثيلاً جديداً من DigitalSignOptions بملف شهادة وتدفق صورة مظهر.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_file_path | `str` | مسار ملف الشهادة الرقمية. |
| appearence_image_stream | `io.RawIOBase` | دفق صورة مظهر التوقيع. |

### مثال

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

ينشئ مثيلاً جديداً من DigitalSignOptions بتدفق شهادة وملف صورة مظهر.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. دفق الشهادة الرقمية. |
| image_file_path | `str` | str. مسار ملف صورة مظهر التوقيع. |

## __init__ {#certificate_stream-appearence_image_stream}

ينشئ مثيلاً جديداً من DigitalSignOptions بتدفق شهادة وتدفق صورة مظهر.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | دفق الشهادة الرقمية. |
| appearence_image_stream | `io.RawIOBase` | دفق صورة مظهر التوقيع. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # تحميل الشهادة وصورة المظهر من التدفقات
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### انظر أيضًا
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
