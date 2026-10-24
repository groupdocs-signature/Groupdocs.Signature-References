---
title: "BarcodeVerifyOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Barkod doğrulama seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/barcodeverifyoptions/
is_root: false
weight: 30
---


## BarcodeVerifyOptions class

Barkod doğrulama seçeneklerini temsil eder.

Daha fazla bilgi edinin
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings

BarcodeVerifyOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/) | Barkod imzası için varsayılan doğrulama seçeneğini başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text) | Doğrulama metni ile bir varsayılan doğrulama seçeneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#encode_type) | Barkod tipi doğrulaması ile bir varsayılan doğrulama seçeneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text-encode_type) | Barkod türü doğrulaması ve metin içeren varsayılan bir doğrulama seçeneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/encode_type/) | Doğrulama için kullanılan barkod türü. |
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
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import BarcodeVerifyOptions


def verify_barcode_signatures():
    with Signature("signed.pdf") as signature:
        options = BarcodeVerifyOptions()
        options.all_pages = True
        options.text = "12345"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document was verified successfully: {len(result.succeeded)} matching barcode signature(s).")
        else:
            print("Document failed verification process.")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
