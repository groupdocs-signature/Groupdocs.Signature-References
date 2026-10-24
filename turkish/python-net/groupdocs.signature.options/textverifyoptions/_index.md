---
title: "TextVerifyOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belge Metin imzasını doğrulamak için seçenekleri tutar."
type: docs
url: /tr/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

Belge Metin imzasını doğrulamak için seçenekleri tutar.

Daha fazla bilgi:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

TextVerifyOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | TextVerifyOptions'ın yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | TextVerifyOptions'ın yeni bir örneğini doğrulama metniyle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | Doğrulanacak metin ve imza uygulama tipi ile yeni bir TextVerifyOptions örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Doğrulanacak form alanının başlığı. Ayarlanırsa, metin yalnızca metin form alanlarında bulunur. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Doğrulanacak form alanı türü; ayarlanırsa, metin yalnızca metin form alanlarında bulunur. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Metin eşleşme türü doğrulaması. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | Doğrulanacak Metin İmzası Kimliği. Sıfırdan büyük olmalıdır; yalnızca PDF belgeleri için desteklenir. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Doğrulanacak imza türü. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Doğrulanacak imza metni. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Her belge sayfasının doğrulanıp doğrulanmayacağını gösteren bayrak. Varsayılan değer True'tir. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Alternatif imza seçenekleri doğrulaması için ek uzantılar. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Geçerli özellik bayrağı. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Doğrulanacak belge sayfa numarası; ayarlanmazsa, belgenin tüm sayfaları ilk oluşum için doğrulanır (minimum değer 1'dir). ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Doğrulanacak sayfaları belirtmek için sayfa seçenekleri. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Üstbilgi/altbilgi imzalarını doğrulamak için belge düzenindeki şekil konumu. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
`TextVerifyOptions` kullanan görev kılavuzları:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
