---
title: "generate_preview methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Genereert een voorbeeld van documentpagina's."
type: docs
url: /nl/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Genereert een voorbeeld van documentpagina's.

Lees meer over hoe u voorbeeldweergaven voor documentpagina's genereert:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| preview_options | `PreviewOptions` | De voorbeeldopties. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Paginanummers zijn 0-gebaseerd: preview_page_0.png is de eerste pagina
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

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
