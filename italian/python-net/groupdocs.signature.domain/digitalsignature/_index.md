---
title: "Classe DigitalSignature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "La classe contiene le proprietà della firma digitale."
type: docs
url: /it/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

La classe contiene le proprietà della firma digitale.

Il tipo DigitalSignature espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | Inizializza una firma digitale con parametri predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | Inizializza una firma digitale con un identificatore di firma noto. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | Inizializza un DigitalSignature utilizzando il primo certificato dal negozio X509 specificato. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | Inizializza un DigitalSignature basato sul negozio X509 specificato e sull'indice del certificato. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | Inizializza una firma digitale con il certificato specificato. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | Clona l'istanza della firma barcode. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | Confronta questa firma con un'altra firma per l'uguaglianza. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | Restituisce il codice hash per la firma digitale. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Carica firme digitali da tutti i negozi di certificati X509 di sistema. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Carica firme digitali da un archivio di certificati. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Carica firme digitali da un archivio di certificati. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Carica firme digitali da un archivio di certificati digitali posizionato in una posizione specifica. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Carica firme digitali da un archivio di certificati digitali posizionato in una posizione specifica. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Il certificato X509 associato alla firma digitale. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Il nome personalizzato del negozio del certificato. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | La posizione dell'archivio del certificato. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Il nome dell'archivio del certificato. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Il commento dello scopo della firma. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | La firma digitale è valida e il documento non è stato manomesso. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | L'ora in cui il documento è stato firmato. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | L'impronta digitale di un certificato. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Il tipo XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
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
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
