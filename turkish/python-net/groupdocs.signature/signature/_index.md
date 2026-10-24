---
title: "Signature sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belge imzalama sürecini kontrol eden ana sınıfı temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Belge imzalama sürecini kontrol eden ana sınıfı temsil eder.

GroupDocs.Signature özellikleri hakkında daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Signature türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Belge bir akış olarak sağlandığında yeni bir Signature örneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Belge akışı ve yükleme seçenekleriyle yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Bir akış tarafından sağlanan belge ve isteğe bağlı [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) ile yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Belge akışı, yükleme seçenekleri ve imza ayarlarıyla yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Dosya yolu ile sağlanan belgeyle yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Dosya yolu ve yükleme seçenekleriyle sağlanan belgeyle yeni bir Signature örneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Dosya yolu ile sağlanan belge ve isteğe bağlı [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) ile yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Dosya yolu, yükleme seçenekleri ve imza ayarlarıyla sağlanan belgeyle yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Belgeden belirtilen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) öğesini siler. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Belgeden sağlanan imza listesini siler. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Belirtilen türdeki imzaları belgeden siler. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Belirtilen `SignatureType` listesindeki imzaları belgeden siler. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Belirli imza kimliğine göre bir imzayı belgeden siler. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Belirtilen imzaları belgeden siler. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | İmza nesnesi tarafından kullanılan iç kaynakları temizler. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Belge sayfalarının önizlemesini oluşturur. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Verilen SignOptions temelinde bir imza önizlemesi oluşturur. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip sayfanın genişliği. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Bir belge içinde imzaları, bir [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) listesi kullanarak arar. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Belgedeki imzaları, sağlanan arama seçeneklerini kullanarak arar ve sonuçları belirtilen koşula göre filtreler. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | `SignatureType` değeriyle belgede belirtilen imza türlerini arar. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Belgedeki imzaları, mevcut tüm arama seçeneklerini kullanarak arar ve sonuçları belirtilen koşula göre filtreler. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Belgeyi [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ile imzalar ve sonucu bir akışa kaydeder. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Bir belgeyi [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ile imzalar ve önceden tanımlı [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) kullanarak sonucu bir akışa kaydeder. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Belgeyi bir [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) koleksiyonu ile imzalar ve sonucu bir akışa kaydeder. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Belgeyi bir [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) koleksiyonu ile imzalar ve önceden tanımlı [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) kullanarak sonucu bir akışa kaydeder. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Belgeyi SignOptions ile imzalar ve sonucu belirtilen dosya yoluna kaydeder. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Belgeyi [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ile imzalar ve önceden tanımlı [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) kullanarak sonucu belirtilen dosya yoluna kaydeder. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Belgeyi bir [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) koleksiyonu ile imzalar ve sonucu belirtilen dosya yoluna kaydeder. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Belgeyi bir [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) koleksiyonu ile imzalar ve önceden tanımlı [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) kullanarak sonucu belirtilen dosya yoluna kaydeder. |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Belgedeki verilen BaseSignature imzasını günceller. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Belgedeki verilen imzaları [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) ile günceller. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Belge imzalarını verilen VerifyOptions verileriyle doğrular. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Belge imzalarını sağlanan doğrulama seçeneklerini kullanarak doğrular ve sonuçları belirtilen koşula göre filtreler. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Belge imzalarını bir VerifyOptions listesiyle doğrular. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Sağlanan doğrulama seçeneklerini kullanarak belge imzalarını doğrular ve verilen koşula göre sonuçları filtreler. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Örnek

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
`Signature` kullanan görev kılavuzları:

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

### Ayrıca Bakınız
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
