---
title: "generate_preview मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ पृष्ठों का पूर्वावलोकन उत्पन्न करता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

दस्तावेज़ पृष्ठों का पूर्वावलोकन उत्पन्न करता है।

दस्तावेज़ पृष्ठों के लिए प्रीव्यू कैसे जेनरेट करें, इस बारे में अधिक जानें:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| preview_options | `PreviewOptions` | प्रीव्यू विकल्प। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # पृष्ठ संख्याएँ 0-आधारित हैं: preview_page_0.png पहला पृष्ठ है
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
