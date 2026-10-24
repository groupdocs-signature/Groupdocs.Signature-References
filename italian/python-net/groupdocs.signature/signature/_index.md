---
title: "Classe Signature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta la classe principale che controlla il processo di firma del documento."
type: docs
url: /it/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Rappresenta la classe principale che controlla il processo di firma del documento.

Scopri di più sulle funzionalità di GroupDocs.Signature:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Il tipo Signature espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Inizializza una nuova istanza di Signature con un documento fornito come stream. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con uno stream del documento e opzioni di caricamento. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento fornito tramite stream e opzionale [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con uno stream del documento, opzioni di caricamento e impostazioni di firma. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento fornito tramite percorso file. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Inizializza una nuova istanza di Signature con il documento fornito tramite percorso file e opzioni di caricamento. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con il documento fornito tramite percorso file e opzionale [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Inizializza una nuova istanza di [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento fornito tramite percorso file, opzioni di caricamento e impostazioni di firma. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Elimina il [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) specificato dal documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Elimina l'elenco fornito di firme dal documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Elimina le firme del tipo specificato dal documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Elimina le firme dell'elenco `SignatureType` specificato dal documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Elimina una firma dal documento tramite il suo ID firma specifico. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Elimina le firme specificate dal documento. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Pulisce le risorse interne utilizzate dall'oggetto firma. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Genera l'anteprima delle pagine del documento. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Genera un'anteprima della firma basata sulle SignOptions fornite. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Cerca firme in un documento utilizzando un elenco di [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Cerca firme nel documento utilizzando le opzioni di ricerca fornite e filtra i risultati in base al predicato specificato. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Cerca i tipi di firma specificati nel documento per valore `SignatureType`. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Cerca firme nel documento utilizzando tutte le opzioni di ricerca disponibili e filtra i risultati in base al predicato specificato. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Firma il documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato in uno stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Firma un documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato in uno stream utilizzando i [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefiniti. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Firma il documento con una raccolta di [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato in uno stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Firma il documento con una raccolta di [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato in uno stream utilizzando i [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefiniti. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Firma il documento con SignOptions e salva il risultato nel percorso file specificato. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Firma il documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato nel percorso file specificato utilizzando i [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefiniti. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Firma il documento con una raccolta di [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato nel percorso file specificato. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Firma il documento con una raccolta di [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato nel percorso file specificato utilizzando i [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefiniti. |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Aggiorna la BaseSignature della firma fornita nel documento. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Aggiorna le firme [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) fornite nel documento. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Verifica le firme del documento con i dati VerifyOptions forniti. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Verifica le firme del documento utilizzando le opzioni di verifica fornite e filtra i risultati in base al predicato specificato. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Verifica le firme del documento con un elenco di dati VerifyOptions. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Verifica le firme dei documenti utilizzando le opzioni di verifica fornite e filtra i risultati con il predicato specificato. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Guide operative che utilizzano `Signature`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Vedi anche
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
