---
title: "méthode generate_preview"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Génère un aperçu des pages du document."
type: docs
url: /fr/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Génère un aperçu des pages du document.

En savoir plus sur la façon de générer des aperçus pour les pages de document :
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Les options d'aperçu. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Les numéros de page commencent à 0 : preview_page_0.png est la première page
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

### Voir aussi
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
