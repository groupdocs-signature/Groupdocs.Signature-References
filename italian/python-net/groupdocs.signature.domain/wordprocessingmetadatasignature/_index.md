---
title: "Classe WordProcessingMetadataSignature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta una firma di metadati Word Processing."
type: docs
url: /it/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/
is_root: false
weight: 840
---


## WordProcessingMetadataSignature class

Rappresenta una firma di metadati Word Processing.

Usato con [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) per aggiungere firme di metadati ai documenti di elaborazione testi.

Il tipo WordProcessingMetadataSignature espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/#name) | Inizializza un WordProcessingMetadataSignature con il nome specificato e un valore vuoto. |
| [__init__](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/#name-value) | Inizializza una firma di metadati WordProcessing con valori predefiniti. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone/) | Clona l'istanza di Metadata Signature. |
| [clone](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone/#value) | Crea un clone dell'istanza WordProcessingMetadataSignature con il valore specificato. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone_object/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/) | Converte la firma metadata in una stringa. |
| [to_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/#format-provider) | Converte la firma di metadati in una stringa con il formato specificato. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string_string/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals/) | Determina se la firma specificata è uguale a questa istanza. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [equals_object](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals_object/) | (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_hash_code/) | Restituisce il codice hash per la firma di metadati. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_boolean/) | Converte in booleano. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/) | Converte il valore della firma di metadati in un datetime. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time_iformat_provider/) | (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/) | Converte il valore della firma di metadati in Decimal. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal_iformat_provider/) | (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double/) | Converte il valore della firma di metadati in un float. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double_iformat_provider/) | (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_integer](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_integer/) | Converte il valore della firma di metadati in un intero. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single/) | Converte il valore della firma di metadati in un float. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single_iformat_provider/) | (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | La data di creazione della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | L'implementazione di [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) utilizzata per codificare e decodificare le proprietà del valore della firma. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Il flag che indica se questa firma è stata eliminata dal documento. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | L'altezza della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Il flag che indica se questo componente rappresenta una firma (`True`) o il contenuto del documento (`False`). (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | La posizione sinistra della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | La data di modifica della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | Il nome univoco dei metadati. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Il numero di pagina in cui è stata trovata la firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | L'identificatore univoco della firma, utilizzato per modificare la firma nel documento tramite operazioni di aggiornamento o eliminazione. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Il tipo di firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | La posizione superiore della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | Il tipo di valore dei metadati. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | L'oggetto dei metadati. (eredita da [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | La larghezza della firma. (eredita da [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Esempio

```python
from datetime import datetime

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
