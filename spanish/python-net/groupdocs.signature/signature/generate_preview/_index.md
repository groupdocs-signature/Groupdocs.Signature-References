---
title: "Método generate_preview"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Genera una vista previa de las páginas del documento."
type: docs
url: /es/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Genera una vista previa de las páginas del documento.

Aprende más sobre cómo generar vistas previas para páginas de documentos:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Las opciones de vista previa. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Los números de página son base 0: preview_page_0.png es la primera página
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

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
