---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

सर्टिफ़िकेट फ़ाइल के साथ नया DigitalSignOptions इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_file_path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_file_path | `str` | डिजिटल प्रमाणपत्र फ़ाइल पथ। |

### उदाहरण

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

सर्टिफ़िकेट स्ट्रीम के साथ नया DigitalSignOptions इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | डिजिटल प्रमाणपत्र स्ट्रीम। |

### उदाहरण

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

सर्टिफ़िकेट फ़ाइल और एक एपीयरेंस इमेज फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_file_path | `str` | डिजिटल प्रमाणपत्र फ़ाइल पथ। |
| image_file_path | `str` | हस्ताक्षर उपस्थिति छवि फ़ाइल पथ। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # सर्टिफ़िकेट और अपीयरेंस इमेज को कन्स्ट्रक्टर में पास करें
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

सर्टिफ़िकेट फ़ाइल और एक एपीयरेंस इमेज स्ट्रीम के साथ DigitalSignOptions का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_file_path | `str` | डिजिटल प्रमाणपत्र फ़ाइल पथ। |
| appearence_image_stream | `io.RawIOBase` | हस्ताक्षर उपस्थिति छवि स्ट्रीम। |

### उदाहरण

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

सर्टिफ़िकेट स्ट्रीम और एक एपीयरेंस इमेज फ़ाइल के साथ DigitalSignOptions का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. डिजिटल प्रमाणपत्र स्ट्रीम। |
| image_file_path | `str` | str. हस्ताक्षर उपस्थिति छवि फ़ाइल पथ। |

## __init__ {#certificate_stream-appearence_image_stream}

सर्टिफ़िकेट स्ट्रीम और एक एपीयरेंस इमेज स्ट्रीम के साथ नया DigitalSignOptions इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | डिजिटल प्रमाणपत्र स्ट्रीम। |
| appearence_image_stream | `io.RawIOBase` | हस्ताक्षर उपस्थिति छवि स्ट्रीम। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # स्ट्रीम से प्रमाणपत्र और उपस्थिति छवि लोड करें
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### संबंधित देखें
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
