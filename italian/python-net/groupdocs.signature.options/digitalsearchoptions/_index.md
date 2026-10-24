---
title: "Classe DigitalSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di ricerca per le firme Digital."
type: docs
url: /it/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

Rappresenta le opzioni di ricerca per le firme Digital.

Maggiori informazioni

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

Il tipo DigitalSearchOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | Inizializza una nuova istanza della classe DigitalSearchOptions con i valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | I commenti della firma digitale da cercare. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | Il nome distinto dell'emittente del certificato da cercare quando il valore non è vuoto. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | L'intervallo di data e ora della firma digitale da cercare. I valori nullabili saranno ignorati. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | La fine dell'intervallo di data e ora delle firme digitali da cercare. Un valore nullo sarà ignorato. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | Il nome distinto del soggetto del certificato da cercare quando viene fornito un valore non vuoto. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Il flag che indica se eseguire la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è True. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Il numero di pagina del documento per la ricerca (opzionale). (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Le opzioni per specificare le pagine per la ricerca della firma. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Il flag che indica se restituire la posizione della forma nel layout del documento. Disponibile solo per i documenti Word. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Il flag per restituire solo le firme contrassegnate come `IsSignature`. Per impostazione predefinita il valore è `False`, il che indica che vengono restituite tutte le firme che corrispondono ai criteri specificati. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
