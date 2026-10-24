---
title: "TextSearchOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metin imzaları için arama seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

Metin imzaları için arama seçeneklerini temsil eder.

Daha fazla bilgi:
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

TextSearchOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | TextSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | TextSearchOptions sınıfının yeni bir örneğini bir metin değeriyle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | Arama için kullanılan metin eşleşme türü. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | Aranacak metin imzası uygulaması. |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | Arama sırasında eşleşecek imza metni. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Her belge sayfasında arama yapılıp yapılmayacağını belirten bayrak. Varsayılan olarak bu değer True'tır. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Arama için belge sayfa numarası (isteğe bağlı). (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | İmza araması için sayfaları belirtmek üzere seçenekler. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Belge düzeninde şekil konumunun döndürülüp döndürülmeyeceğini belirten bayrak. Yalnızca Word belgeleri için kullanılabilir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` olarak işaretlenmiş yalnızca imzaları döndürmek için bayrak. Varsayılan değer `False` olup, belirtilen kriterlere uyan tüm imzaların döndürüleceğini gösterir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    options = TextSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.text = "John"
    options.match_type = TextMatchType.CONTAINS
    options.signature_implementation = TextSignatureImplementation.NATIVE

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching text signature(s)")
    for ts in result.signatures:
        print(f"'{ts.text}' on page {ts.page_number} at ({ts.left}, {ts.top}), size {ts.width}x{ts.height}")
```

### Guides
`TextSearchOptions` kullanan görev kılavuzları:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
