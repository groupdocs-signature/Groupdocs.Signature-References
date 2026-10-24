---
title: "Classe PreviewOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di anteprima del documento."
type: docs
url: /it/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Rappresenta le opzioni di anteprima del documento.

Il tipo PreviewOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | L'altezza delle immagini di anteprima. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | Il flag che indica se le firme sono nascoste dalle immagini di anteprima della pagina. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | I numeri di pagina delle immagini di anteprima. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Il formato delle immagini di anteprima. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | La risoluzione delle immagini di anteprima in DPI (punti per pollice). La risoluzione predefinita è 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | La larghezza dell'immagine di anteprima. |

### Esempio

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
Guide operative che utilizzano `PreviewOptions`:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
