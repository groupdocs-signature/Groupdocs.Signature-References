---
title: "classe ImageSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di ricerca per le firme immagine."
type: docs
url: /it/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

Rappresenta le opzioni di ricerca per le firme immagine.

Per saperne di più:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

Il tipo ImageSearchOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | Inizializza una nuova istanza della classe ImageSearchOptions con valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | La dimensione massima delle immagini per i criteri di ricerca, in byte. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | La dimensione minima dei dati immagine, in byte, da considerare durante una ricerca. Un valore diverso da zero specifica la dimensione minima; il valore predefinito è zero, che non influisce sul risultato della ricerca. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | Il flag che determina se il contenuto immagine di una firma viene restituito. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | Il tipo di file del contenuto immagine restituito quando la proprietà `return_content` è abilitata. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Il flag che indica se eseguire la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è True. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Il numero di pagina del documento per la ricerca (opzionale). (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Le opzioni per specificare le pagine per la ricerca della firma. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Il flag che indica se restituire la posizione della forma nel layout del documento. Disponibile solo per i documenti Word. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Il flag per restituire solo le firme contrassegnate come `IsSignature`. Per impostazione predefinita il valore è `False`, il che indica che vengono restituite tutte le firme che corrispondono ai criteri specificati. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
