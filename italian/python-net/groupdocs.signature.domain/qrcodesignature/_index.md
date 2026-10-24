---
title: "Classe QrCodeSignature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le proprietà della firma QR-code."
type: docs
url: /it/python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 550
---


## QrCodeSignature class

Rappresenta le proprietà della firma QR-code.

Il tipo QrCodeSignature espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#signature_id) | Inizializza un oggetto QrCodeSignature con un identificatore di firma ottenuto dopo un processo di ricerca. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/) | Clona l'istanza della firma QR-Code. |
| [equals](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals/#obj) | Determina se l'oggetto firma fornito è uguale a questa istanza. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_hash_code/) | Sovrascrive il metodo GetHashCode. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content/) | Il contenuto dell'immagine dati binari QR-code di tipo [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type/) | Il tipo di codifica QR-code. |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) | Il formato dell'immagine della firma QR-code. |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text/) | Il testo del QR-code. |
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
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    if result.signatures:
        qr = result.signatures[0]
        print(qr.text, qr.encode_type.type_name, qr.left, qr.top)
```

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
