---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature.options import ImageSignOptions

# इमेज फ़ाइल पाथ का उपयोग करके इमेज सिग्नेचर विकल्प बनाएं
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

ImageSignOptions को एक इमेज फ़ाइल के साथ इनिशियलाइज़ करता है।

```python
def __init__(self, image_file_path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_file_path | `str` | इमेज फ़ाइल पाथ। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # यहाँ अतिरिक्त विकल्प कॉन्फ़िगर करें, जैसे कि स्थिति, आकार, आदि।
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

इमेज स्ट्रीम के साथ एक नया ImageSignOptions इंस्टेंस इनिशियलाइज़ करता है।

```python
def __init__(self, image_stream):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | इमेज स्ट्रीम। |

### उदाहरण

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

### संबंधित देखें
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
