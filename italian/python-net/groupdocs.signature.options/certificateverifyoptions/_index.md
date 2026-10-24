---
title: "Classe CertificateVerifyOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Mantiene le opzioni per verificare i documenti del certificato."
type: docs
url: /it/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Mantiene le opzioni per verificare i documenti del certificato.

Maggiori informazioni

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

Il tipo CertificateVerifyOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Inizializza una nuova istanza di TextVerifyOptions con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Inizializza una nuova istanza di CertificateVerifyOptions con il soggetto da verificare. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | La proprietà indica se il certificato è scaduto in base al risultato della convalida. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | L'emittente del certificato da verificare. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | Il tipo di corrispondenza del testo utilizzato per la verifica. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | Il processo di verifica dovrebbe fornire la convalida della catena X.509 utilizzando la politica di convalida di base. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | Il numero di serie del certificato da verificare. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | Il soggetto del certificato da verificare. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | L'impronta digitale del certificato da verificare. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Il flag indica se ogni pagina del documento deve essere verificata. Per impostazione predefinita il valore è True. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Le estensioni aggiuntive per la verifica delle opzioni di firma alternative. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Il flag della proprietà valida. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Il numero di pagina del documento da verificare; se non impostato, tutte le pagine del documento sono verificate per la prima occorrenza (valore minimo è 1). (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Le opzioni di pagina per specificare le pagine da verificare. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La posizione della forma nel layout del documento utilizzata per verificare le firme in intestazioni/piè di pagina. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
