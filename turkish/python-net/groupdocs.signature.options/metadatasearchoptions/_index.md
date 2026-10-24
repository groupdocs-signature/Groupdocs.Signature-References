---
title: "MetadataSearchOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Meta veri imzaları için arama seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

Meta veri imzaları için arama seçeneklerini temsil eder.

Bir belgede meta veri imzalarını aramayı yapılandırmak için seçenekler sağlar.

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

MetadataSearchOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | MetadataSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | Bu seçenek koleksiyonundaki tüm meta veri imzalarını çözmek için kullanılan [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) uygulaması. |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | Arama sonucuna belge istatistikleri ve bilgileri gibi yerleşik belge özelliklerinin dahil edilip edilmeyeceğini belirten bayrak. |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | Aranacak ve eşleşecek meta veri imza adı. |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | Arama için kullanılan meta veri adı eşleşme türü. Yalnızca `name` özelliği ayarlandığında uygulanır. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Her belge sayfasında arama yapılıp yapılmayacağını belirten bayrak. Varsayılan olarak bu değer True'tır. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Arama için belge sayfa numarası (isteğe bağlı). (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | İmza araması için sayfaları belirtmek üzere seçenekler. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Belge düzeninde şekil konumunun döndürülüp döndürülmeyeceğini belirten bayrak. Yalnızca Word belgeleri için kullanılabilir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` olarak işaretlenmiş yalnızca imzaları döndürmek için bayrak. Varsayılan değer `False` olup, belirtilen kriterlere uyan tüm imzaların döndürüleceğini gösterir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
