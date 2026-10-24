---
title: "QrCodeVerifyOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belge QR-kod imzasını doğrulamak için seçenekleri tutar."
type: docs
url: /tr/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

Belge QR-kod imzasını doğrulamak için seçenekleri tutar.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

QrCodeVerifyOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | QR-Kod imzaları için doğrulama seçeneklerini başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | Belirtilen QR-kod metniyle QR-Kod imzaları için doğrulama seçeneklerini başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | Doğrulanacak metin ve QR-Kod kodlama türüyle QR-Kod imzaları için doğrulama seçeneklerini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | QR-Code imza metin özelliklerini kodlamak ve çözmek için kullanılan [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) uygulaması. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | QR-code türü doğrulaması. Bu özellik isteğe bağlıdır. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Her belge sayfasının doğrulanıp doğrulanmayacağını gösteren bayrak. Varsayılan değer True'tir. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Alternatif imza seçenekleri doğrulaması için ek uzantılar. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Doğrulanacak form alanının başlığı. Ayarlanırsa, metin yalnızca metin form alanlarında bulunur. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Doğrulanacak form alanının türü; ayarlanırsa, metin yalnızca metin form alanlarında bulunur. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Geçerli özellik bayrağı. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Metin eşleşme türü doğrulaması. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Doğrulanacak belge sayfa numarası; ayarlanmazsa, belgenin tüm sayfaları ilk oluşum için doğrulanır (minimum değer 1'dir). ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Doğrulanacak sayfaları belirtmek için sayfa seçenekleri. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Üstbilgi/altbilgi imzalarını doğrulamak için belge düzenindeki şekil konumu. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | Doğrulanacak Metin İmza Kimliği. Sıfırdan büyük olmalıdır; yalnızca PDF belgeleri için desteklenir. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Doğrulanacak imzanın türü. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Doğrulanacak imza metni. (inherited from [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
