---
title: "Classe ImageSignature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "La classe contiene le proprietà della firma immagine."
type: docs
url: /it/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

La classe contiene le proprietà della firma immagine.

Il tipo ImageSignature espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | Inizializza un oggetto ImageSignature con un identificatore di firma univoco ottenuto dal metodo Sign o Search della classe [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | Clona l'istanza ImageSignature. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | Determina se la firma specificata è uguale a questa istanza. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | Restituisce il codice hash per la firma. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | I dati binari dell'immagine della firma, nel formato specificato da [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | Il formato dell'immagine della firma. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | La dimensione in byte dell'immagine della firma. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | La data di creazione della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Il flag che indica se questa firma è stata eliminata dal documento. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | L'altezza della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Il flag che indica se questo componente rappresenta una firma (`True`) o il contenuto del documento (`False`). (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | La posizione sinistra della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | La data di modifica della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Il numero di pagina in cui è stata trovata la firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | L'identificatore univoco della firma, utilizzato per modificare la firma nel documento tramite operazioni di aggiornamento o eliminazione. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Il tipo di firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | La posizione superiore della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | La larghezza della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
