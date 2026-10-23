---
title: "PreviewOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Dokumentvorschau-Optionen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Stellt Dokumentvorschau-Optionen dar.

Der Typ PreviewOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | Die Höhe der Vorschaubilder. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | Das Flag, das angibt, ob Signaturen in den Seitenvorschau-Bildern ausgeblendet sind. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | Die Seitenzahlen der Vorschaubilder. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Das Format der Vorschaubilder. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | Die Auflösung der Vorschaubilder in DPI (dots per inch). Die Standardauflösung beträgt 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | Die Breite des Vorschaubildes. |

### Beispiel

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
Aufgabenleitfäden, die `PreviewOptions` verwenden:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
