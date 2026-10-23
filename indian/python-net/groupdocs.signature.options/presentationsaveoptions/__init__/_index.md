---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ एक नया PresentationSaveOptions इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/presentationsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ एक नया PresentationSaveOptions इंस्टेंस प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट के साथ PresentationSaveOptions का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, file_format):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_format | `PresentationSaveFileFormat` | आउटपुट फ़ाइल प्रकार। |

## __init__ {#overwrite_existing_file}

निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ PresentationSaveOptions का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, overwrite_existing_file):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| overwrite_existing_file | `bool` | फ़्लैग कि क्या साइन किए गए फ़ाइल को उसी फ़ाइल से अधिलेखित किया जाए। |

## __init__ {#file_format-overwrite_existing_file}

निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट और ओवरराइट फ़्लैग के साथ PresentationSaveOptions का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_format | `PresentationSaveFileFormat` | आउटपुट फ़ाइल प्रकार `PresentationSaveFileFormat`। |
| overwrite_existing_file | `bool` | फ़्लैग जो यह दर्शाता है कि मौजूदा हस्ताक्षरित फ़ाइल को ओवरराइट करना है या नहीं। |

### संबंधित देखें
* class [`PresentationSaveOptions`](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/)
