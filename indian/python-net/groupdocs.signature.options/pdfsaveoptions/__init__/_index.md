---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

निर्दिष्ट आउटपुट फ़ाइल स्वरूप के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, file_format):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | आउटपुट फ़ाइल प्रकार `PdfSaveFileFormat`। |

## __init__ {#overwrite_existing_file}

ओवरराइट फ़्लैग के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, overwrite_existing_file):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| overwrite_existing_file | `bool` | फ़्लैग कि क्या साइन किए गए फ़ाइल को उसी फ़ाइल से अधिलेखित किया जाए। |

## __init__ {#file_format-overwrite_existing_file}

निर्दिष्ट आउटपुट फ़ाइल स्वरूप और ओवरराइट फ़्लैग के साथ PdfSaveOptions का नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | आउटपुट फ़ाइल प्रकार। |
| overwrite_existing_file | `bool` | फ़्लैग कि क्या साइन किए गए फ़ाइल को उसी फ़ाइल से अधिलेखित किया जाए। |

### उदाहरण

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# PDF फ़ॉर्मेट के साथ सहेजने के विकल्प बनाएं और मौजूदा फ़ाइलों को ओवरराइट करने की अनुमति दें
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### संबंधित देखें
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
