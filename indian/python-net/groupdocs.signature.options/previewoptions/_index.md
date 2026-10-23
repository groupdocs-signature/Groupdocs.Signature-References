---
title: "PreviewOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ प्रीव्यू विकल्पों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

दस्तावेज़ प्रीव्यू विकल्पों का प्रतिनिधित्व करता है।

PreviewOptions प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### गुण
| गुण | विवरण |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | पूर्वावलोकन छवियों की ऊँचाई। |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | फ़्लैग जो दर्शाता है कि हस्ताक्षर पृष्ठ पूर्वावलोकन छवियों से छिपे हैं या नहीं। |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | पूर्वावलोकन छवियों के पृष्ठ संख्याएँ। |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | पूर्वावलोकन छवियों का फ़ॉर्मेट। |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | पूर्वावलोकन छवियों का रिज़ॉल्यूशन DPI (डॉट्स प्रति इंच) में है। डिफ़ॉल्ट रिज़ॉल्यूशन 96 DPI है। |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | पूर्वावलोकन छवि की चौड़ाई। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

with Signature("sample.pdf") as signature:
    preview_options = PreviewOptions(create_page_stream)
    preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
    signature.generate_preview(preview_options)
```

### Guides
`PreviewOptions` का उपयोग करने वाले कार्य गाइड:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
