---
title: "PreviewOptions clase"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa opciones de vista previa del documento."
type: docs
url: /es/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Representa opciones de vista previa del documento.

El tipo PreviewOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | La altura de las imágenes de vista previa. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | La bandera que indica si las firmas están ocultas de las imágenes de vista previa de la página. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | Los números de página de las imágenes de vista previa. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | El formato de las imágenes de vista previa. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | La resolución de las imágenes de vista previa en DPI (puntos por pulgada). La resolución predeterminada es 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | El ancho de la imagen de vista previa. |

### Ejemplo

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
Guías de tareas que usan `PreviewOptions`:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
