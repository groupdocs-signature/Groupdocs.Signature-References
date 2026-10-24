---
title: "Klassen Signature"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar huvudklassen som styr dokumentets signeringsprocess."
type: docs
url: /sv/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Representerar huvudklassen som styr dokumentets signeringsprocess.

Läs mer om funktionerna i GroupDocs.Signature:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Typen Signature visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Initierar en ny Signature-instans med ett dokument som tillhandahålls som en ström. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Initierar en ny [`Signature`](/signature/python-net/groupdocs.signature/signature/) instans med ett dokumentflöde och inläsningsalternativ. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Initierar en ny [`Signature`](/signature/python-net/groupdocs.signature/signature/) instans med ett dokument som tillhandahålls av ett flöde och valfria [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Initierar en ny instans av [`Signature`](/signature/python-net/groupdocs.signature/signature/) med ett dokumentflöde, inläsningsalternativ och signaturinställningar. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Initierar en ny instans av [`Signature`](/signature/python-net/groupdocs.signature/signature/) med ett dokument som tillhandahålls via filväg. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Initierar en ny Signature-instans med dokumentet som tillhandahålls via filväg och inläsningsalternativ. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Initierar en ny [`Signature`](/signature/python-net/groupdocs.signature/signature/) instans med dokumentet som tillhandahålls via en filväg och valfria [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Initierar en ny instans av [`Signature`](/signature/python-net/groupdocs.signature/signature/) med ett dokument som tillhandahålls via filväg, inläsningsalternativ och signaturinställningar. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Tar bort den angivna [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) från dokumentet. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Tar bort den angivna listan med signaturer från dokumentet. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Tar bort signaturer av den angivna typen från dokumentet. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Tar bort signaturer från den angivna `SignatureType`-listan i dokumentet. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Tar bort en signatur med dess specifika signatur‑Id från dokumentet. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Tar bort de angivna signaturerna från dokumentet. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Rensar upp interna resurser som används av signaturobjektet. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Genererar förhandsgranskning av dokumentsidor. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Genererar en signaturförhandsgranskning baserad på de givna SignOptions. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Hämtar information om dokumentsidor: deras storlekar, maximal sidhöjd, bredden på en sida med maximal höjd. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Söker efter signaturer i ett dokument med hjälp av en lista med [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Söker efter signaturer i dokumentet med de angivna sökalternativen och filtrerar resultaten baserat på det angivna predikatet. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Söker efter angivna signaturtyper i dokumentet efter `SignatureType`‑värde. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Söker efter signaturer i dokumentet med alla tillgängliga sökalternativ och filtrerar resultaten baserat på det angivna predikatet. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Signerar dokument med [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till ett flöde. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Signerar ett dokument med [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till ett flöde med fördefinierade [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Signerar dokument med en samling av [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till ett flöde. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Signerar dokument med en samling av [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till ett flöde med fördefinierade [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Signerar dokument med SignOptions och sparar resultatet till angiven filsökväg. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Signerar dokument med [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till angiven filsökväg med fördefinierade [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Signerar dokument med en samling av [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till angiven filsökväg. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Signerar dokumentet med en samling av [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till den angivna filsökvägen med fördefinierade [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Uppdaterar den överförda signaturen BaseSignature i dokumentet. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Uppdaterar de överförda signaturerna [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) i dokumentet. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Verifierar dokumentets signaturer med angivna VerifyOptions-data. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Verifierar dokumentets signaturer med de tillhandahållna verifieringsalternativen och filtrerar resultaten baserat på det angivna predikatet. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Verifierar dokumentets signaturer med en lista av VerifyOptions-data. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Verifierar dokumentets signaturer med de tillhandahållna verifieringsalternativen och filtrerar resultaten med det givna predikatet. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Exempel

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
Uppgiftsguider som använder `Signature`:

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

### Se även
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
