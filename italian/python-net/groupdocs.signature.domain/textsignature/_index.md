---
title: "Classe TextSignature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "La classe TextSignature contiene le proprietà della firma di testo."
type: docs
url: /it/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

La classe TextSignature contiene le proprietà della firma di testo.

Il tipo TextSignature espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | Inizializza un oggetto TextSignature con l'identificatore unico della firma ottenuto da un'operazione di firma o ricerca. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Clona l'istanza di Text Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Confronta la firma specificata con questa istanza per l'uguaglianza. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | Restituisce il codice hash per la firma. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | L'attributo nativo che indica se la firma è specifica al documento. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | L'implementazione della firma di testo. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | Il testo della firma. |
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
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
