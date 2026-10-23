---
title: "Κλάση PreviewOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές προεπισκόπησης εγγράφου."
type: docs
url: /el/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Αντιπροσωπεύει τις επιλογές προεπισκόπησης εγγράφου.

Ο τύπος PreviewOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | Το ύψος των εικόνων προεπισκόπησης. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | Η σημαία που υποδεικνύει εάν οι υπογραφές είναι κρυμμένες από τις εικόνες προεπισκόπησης σελίδας. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | Οι αριθμοί σελίδων των εικόνων προεπισκόπησης. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Η μορφή των εικόνων προεπισκόπησης. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | Η ανάλυση των εικόνων προεπισκόπησης σε DPI (σημεία ανά ίντσα). Η προεπιλεγμένη ανάλυση είναι 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | Το πλάτος της εικόνας προεπισκόπησης. |

### Παράδειγμα

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
Οδηγοί εργασιών που χρησιμοποιούν `PreviewOptions`:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
