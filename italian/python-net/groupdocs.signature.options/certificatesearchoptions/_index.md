---
title: "Classe CertificateSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di ricerca per le firme di metadati del certificato."
type: docs
url: /it/python-net/groupdocs.signature.options/certificatesearchoptions/
is_root: false
weight: 60
---


## CertificateSearchOptions class

Rappresenta le opzioni di ricerca per le firme di metadati del certificato.

Maggiori informazioni

- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: Advanced search within Digital Certificate X509 documents (https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

Il tipo CertificateSearchOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/) | Inizializza una nuova istanza della classe TextSearchOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/#text) | Inizializza una nuova istanza della classe TextSearchOptions con il valore del testo. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/match_type/) | Il tipo di corrispondenza del testo utilizzato per la ricerca. |
| [text](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/text/) | Il testo della proprietà certificate da confrontare durante la ricerca. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Il flag che indica se eseguire la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è True. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Il numero di pagina del documento per la ricerca (opzionale). (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Le opzioni per specificare le pagine per la ricerca della firma. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Il flag che indica se restituire la posizione della forma nel layout del documento. Disponibile solo per i documenti Word. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Il flag per restituire solo le firme contrassegnate come `IsSignature`. Per impostazione predefinita il valore è `False`, il che indica che vengono restituite tutte le firme che corrispondono ai criteri specificati. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
