---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the DigitalSignOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the DigitalSignOptions class with default values.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Initializes a new DigitalSignOptions instance with a certificate file.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Digital certificate file path. |

### Example

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

Initializes a new DigitalSignOptions instance with a certificate stream.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Digital Certificate stream. |

### Example

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

Initializes a new instance of the DigitalSignOptions class with a certificate file and an appearance image file.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Digital certificate file path. |
| image_file_path | `str` | Signature appearance image file path. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Pass the certificate and the appearance image to the constructor
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Initializes a new instance of DigitalSignOptions with a certificate file and an appearance image stream.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_file_path | `str` | Digital certificate file path. |
| appearence_image_stream | `io.RawIOBase` | Signature appearance image stream. |

### Example

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

Initializes a new instance of DigitalSignOptions with a certificate stream and an appearance image file.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Digital Certificate stream. |
| image_file_path | `str` | str. Signature Appearance image file path. |

## __init__ {#certificate_stream-appearence_image_stream}

Initializes a new DigitalSignOptions instance with a certificate stream and an appearance image stream.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Digital Certificate stream. |
| appearence_image_stream | `io.RawIOBase` | Signature appearance image stream. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Load certificate and appearance image from streams
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### See Also
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
