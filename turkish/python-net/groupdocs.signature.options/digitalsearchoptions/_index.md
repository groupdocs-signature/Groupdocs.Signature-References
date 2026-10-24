---
title: "DigitalSearchOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Dijital imzalar için arama seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

Dijital imzalar için arama seçeneklerini temsil eder.

Daha fazla bilgi edinin

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

DigitalSearchOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | DigitalSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | Aranacak dijital imzanın yorumları. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | Değer boş olmadığında aranacak sertifika sağlayıcısının ayırt edici adı. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | Aranacak dijital imzanın tarih ve saat aralığı. Boş değer yok sayılacaktır. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | Aranacak dijital imzaların tarih ve saat aralığının sonu. Boş değer yok sayılacaktır. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | Boş olmayan bir değer sağlandığında aranacak sertifikanın ayırt edici konu adı. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Her belge sayfasında arama yapılıp yapılmayacağını belirten bayrak. Varsayılan olarak bu değer True'tır. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Arama için belge sayfa numarası (isteğe bağlı). (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | İmza araması için sayfaları belirtmek üzere seçenekler. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Belge düzeninde şekil konumunun döndürülüp döndürülmeyeceğini belirten bayrak. Yalnızca Word belgeleri için kullanılabilir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` olarak işaretlenmiş yalnızca imzaları döndürmek için bayrak. Varsayılan değer `False` olup, belirtilen kriterlere uyan tüm imzaların döndürüleceğini gösterir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
