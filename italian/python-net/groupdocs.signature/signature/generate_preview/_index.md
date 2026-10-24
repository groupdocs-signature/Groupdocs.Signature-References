---
title: "Metodo generate_preview"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Genera l'anteprima delle pagine del documento."
type: docs
url: /it/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Genera l'anteprima delle pagine del documento.

Scopri di più su come generare anteprime per le pagine dei documenti:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Le opzioni di anteprima. |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # I numeri di pagina sono basati su 0: preview_page_0.png è la prima pagina
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

### Vedi anche
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
