---
title: "Methode generate_preview"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Erstellt eine Vorschau der Dokumentseiten."
type: docs
url: /de/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Erstellt eine Vorschau der Dokumentseiten.

Erfahren Sie mehr darüber, wie Vorschaubilder für Dokumentseiten erzeugt werden:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Die Vorschauoptionen. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Page numbers are 0-based: preview_page_0.png is the first page
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

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
