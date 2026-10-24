---
title: "generate_preview-metoden"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Genererar förhandsgranskning av dokumentsidor."
type: docs
url: /sv/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Genererar förhandsgranskning av dokumentsidor.

Läs mer om hur du genererar förhandsvisningar för dokumentsidor:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Förhandsgranskningsalternativen. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Sidnummer är 0-baserade: preview_page_0.png är den första sidan
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

### Se även
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
