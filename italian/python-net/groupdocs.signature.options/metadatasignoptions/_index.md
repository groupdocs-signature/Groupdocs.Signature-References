---
title: "Classe MetadataSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni della firma Metadata."
type: docs
url: /it/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

Rappresenta le opzioni della firma Metadata.

Maggiori informazioni

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

Il tipo MetadataSignOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | Inizializza una nuova istanza della classe MetadataSignOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | Inizializza una nuova istanza di [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) con i metadati. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | Aggiungi un'istanza esistente di MetadataSignature alla raccolta. |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | Crea una nuova ImageMetadataSignature con gli argomenti forniti e la aggiunge alla raccolta. |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | Crea una nuova PdfMetadataSignature con gli argomenti forniti e la aggiunge alla raccolta. |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | L'implementazione di [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) utilizzata per crittografare tutte le firme di metadati in questa raccolta di opzioni. |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | Le firme di metadati associate alla firma. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La firma verrà posizionata su tutte le pagine del documento. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | L'aspetto aggiuntivo della firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Il tipo di documento delle opzioni della firma (`DocumentType`). (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Le estensioni della firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | L'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Il numero di pagina del documento per la firma. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Le opzioni per specificare le pagine da firmare. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Il tipo di firma (`SignatureType`). (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La posizione Z-order della firma di testo, che determina l'ordine di visualizzazione delle firme sovrapposte. (ereditato da [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Esempio

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s).")
```

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
