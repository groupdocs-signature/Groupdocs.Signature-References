---
title: "Classe DigitalVerifyOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Mantiene le opzioni per verificare la firma digitale di un documento."
type: docs
url: /it/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Mantiene le opzioni per verificare la firma digitale di un documento.

Maggiori informazioni

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

Il tipo DigitalVerifyOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Inizializza un'istanza di DigitalVerifyOptions con i valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Inizializza un'istanza di DigitalVerifyOptions con il percorso del file del certificato digitale fornito. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Inizializza un'istanza di DigitalVerifyOptions con lo stream del certificato fornito. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | Il certificato X509Certificate2 ottenuto dal percorso del file o dallo stream del certificato. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Il percorso del file del certificato digitale. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | Lo stream del certificato digitale. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | I commenti della firma digitale da convalidare. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Il contatto della firma da convalidare. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | Il nome dell'emittente del certificato da convalidare. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | La posizione della firma da convalidare. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | La password del certificato digitale, se necessaria. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | Il motivo della firma digitale da convalidare. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | L'inizio dell'intervallo di data e ora della firma digitale da convalidare. Un valore None verrà ignorato. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | La fine dell'intervallo di data e ora della firma digitale da convalidare. Un valore null verrà ignorato. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | Il nome distinto del soggetto del certificato da convalidare; la verifica controlla se il nome del soggetto della firma contiene o è uguale a questo valore sensibile al maiuscolo/minuscolo. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Il flag indica se ogni pagina del documento deve essere verificata. Per impostazione predefinita il valore è True. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Le estensioni aggiuntive per la verifica delle opzioni di firma alternative. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Il flag della proprietà valida. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Il numero di pagina del documento da verificare; se non impostato, tutte le pagine del documento sono verificate per la prima occorrenza (valore minimo è 1). (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Le opzioni di pagina per specificare le pagine da verificare. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La posizione della forma nel layout del documento utilizzata per verificare le firme in intestazioni/piè di pagina. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
