---
title: "MetadataSearchOptions classe"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di ricerca per le firme Metadata."
type: docs
url: /it/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

Rappresenta le opzioni di ricerca per le firme Metadata.

Fornisce opzioni per configurare la ricerca di firme di metadati in un documento.

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

Il tipo MetadataSearchOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | Inizializza una nuova istanza della classe MetadataSearchOptions con i valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | L'implementazione di [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) utilizzata per decrittare tutte le firme di metadati all'interno di questa raccolta di opzioni. |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | Il flag che indica se le proprietà integrate del documento, come le statistiche e le informazioni del documento, sono incluse nel risultato della ricerca. |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | Il nome della firma di metadati da cercare e corrispondere. |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | Il tipo di corrispondenza del nome dei metadati utilizzato per la ricerca. Viene applicato solo quando la proprietà `name` è impostata. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Il flag che indica se eseguire la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è True. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Il numero di pagina del documento per la ricerca (opzionale). (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Le opzioni per specificare le pagine per la ricerca della firma. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Il flag che indica se restituire la posizione della forma nel layout del documento. Disponibile solo per i documenti Word. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Il flag per restituire solo le firme contrassegnate come `IsSignature`. Per impostazione predefinita il valore è `False`, il che indica che vengono restituite tutte le firme che corrispondono ai criteri specificati. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
