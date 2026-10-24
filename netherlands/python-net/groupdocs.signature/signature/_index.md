---
title: "Signature klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt de hoofdklasse voor die het documentondertekeningsproces beheert."
type: docs
url: /nl/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Stelt de hoofdklasse voor die het documentondertekeningsproces beheert.

Leer meer over de functies van GroupDocs.Signature:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Het Signature‑type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Initialiseert een nieuw Signature‑object met een document dat als stream wordt aangeleverd. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Initialiseert een nieuw [`Signature`](/signature/python-net/groupdocs.signature/signature/) object met een document‑stream en laadopties. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Initialiseert een nieuw [`Signature`](/signature/python-net/groupdocs.signature/signature/) object met een document dat via een stream wordt aangeleverd en optionele [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Initialiseert een nieuw exemplaar van [`Signature`](/signature/python-net/groupdocs.signature/signature/) met een document‑stream, laadopties en [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Initialiseert een nieuw exemplaar van [`Signature`](/signature/python-net/groupdocs.signature/signature/) met een document dat via een bestandspad wordt aangeleverd. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Initialiseert een nieuw Signature‑object met het document dat via een bestandspad wordt aangeleverd en laadopties. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Initialiseert een nieuw [`Signature`](/signature/python-net/groupdocs.signature/signature/) object met het document dat via een bestandspad wordt aangeleverd en optionele [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Initialiseert een nieuw exemplaar van [`Signature`](/signature/python-net/groupdocs.signature/signature/) met een document dat via een bestandspad wordt aangeleverd, laadopties en [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Verwijdert de opgegeven [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) uit het document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Verwijdert de opgegeven lijst met handtekeningen uit het document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Verwijdert handtekeningen van het opgegeven type uit het document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Verwijdert handtekeningen van de opgegeven `SignatureType`-lijst uit het document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Verwijdert een handtekening op basis van zijn specifieke handtekening‑Id uit het document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Verwijdert de opgegeven handtekeningen uit het document. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Ruimt interne bronnen op die door het handtekeningobject worden gebruikt. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Genereert een voorbeeld van documentpagina's. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Genereert een handtekeningvoorbeeld op basis van de opgegeven SignOptions. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Haalt informatie op over documentpagina's: hun afmetingen, maximale paginahoogte, de breedte van een pagina met de maximale hoogte. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Zoekt naar handtekeningen in een document met behulp van een lijst van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Zoekt naar handtekeningen in het document met de opgegeven zoekopties en filtert de resultaten op basis van het gespecificeerde predicaat. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Zoekt naar opgegeven handtekeningtypes in het document op basis van de `SignatureType`‑waarde. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Zoekt naar handtekeningen in het document met alle beschikbare zoekopties en filtert de resultaten op basis van het gespecificeerde predicaat. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Ondertekent het document met [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op in een stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Ondertekent een document met [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op in een stream met behulp van vooraf gedefinieerde [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Ondertekent het document met een verzameling van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op in een stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Ondertekent het document met een verzameling van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op in een stream met behulp van vooraf gedefinieerde [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Ondertekent het document met SignOptions en slaat het resultaat op naar het opgegeven bestandspad. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Ondertekent het document met [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Ondertekent het document met een verzameling van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op naar het opgegeven bestandspad. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Ondertekent het document met een verzameling van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Werkt de meegegeven handtekening BaseSignature bij in het document. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Werkt de meegegeven handtekeningen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) bij in het document. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Verifieert de handtekeningen van het document met de opgegeven VerifyOptions-gegevens. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Verifieert de handtekeningen van het document met de opgegeven verificatieopties en filtert de resultaten op basis van het gespecificeerde predicaat. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Verifieert de handtekeningen van het document met een lijst van VerifyOptions-gegevens. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Verifieert documenthandtekeningen met behulp van de opgegeven verificatieopties en filtert de resultaten met de gegeven predicaat. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Voorbeeld

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
Taakgidsen die `Signature` gebruiken:

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

### Zie ook
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
