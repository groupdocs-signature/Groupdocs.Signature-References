---
title: "generate_preview μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί προεπισκόπηση των σελίδων του εγγράφου."
type: docs
url: /el/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Δημιουργεί προεπισκόπηση των σελίδων του εγγράφου.

Μάθετε περισσότερα σχετικά με το πώς να δημιουργήσετε προεπισκοπήσεις για σελίδες εγγράφου:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Οι επιλογές προεπισκόπησης. |

### Παράδειγμα

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Οι αριθμοί σελίδων είναι 0‑βάση: preview_page_0.png είναι η πρώτη σελίδα
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

### Δείτε επίσης
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
