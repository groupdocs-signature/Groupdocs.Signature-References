---
title: "Classe PreviewOptions"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les options d’aperçu du document."
type: docs
url: /fr/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Représente les options d’aperçu du document.

Le type PreviewOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | La hauteur des images d'aperçu. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | Le drapeau indiquant si les signatures sont masquées des images d'aperçu de page. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | Les numéros de page des images d'aperçu. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Le format des images d'aperçu. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | La résolution des images d'aperçu en DPI (points par pouce). La résolution par défaut est de 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | La largeur de l'image d'aperçu. |

### Exemple

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
Guides de tâches qui utilisent `PreviewOptions` :

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Voir aussi
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
