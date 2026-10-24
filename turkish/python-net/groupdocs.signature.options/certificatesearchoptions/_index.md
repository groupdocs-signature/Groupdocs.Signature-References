---
title: "CertificateSearchOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Sertifika meta verisi imzaları için arama seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/certificatesearchoptions/
is_root: false
weight: 60
---


## CertificateSearchOptions class

Sertifika meta verisi imzaları için arama seçeneklerini temsil eder.

Daha fazla bilgi edinin

- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: Advanced search within Digital Certificate X509 documents (https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

CertificateSearchOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/) | TextSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/#text) | TextSearchOptions sınıfının yeni bir örneğini metin değeriyle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/match_type/) | Arama için kullanılan metin eşleşme türü. |
| [text](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/text/) | Aramada eşleşecek sertifika özelliği metni. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Her belge sayfasında arama yapılıp yapılmayacağını belirten bayrak. Varsayılan olarak bu değer True'tır. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Arama için belge sayfa numarası (isteğe bağlı). (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | İmza araması için sayfaları belirtmek üzere seçenekler. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Belge düzeninde şekil konumunun döndürülüp döndürülmeyeceğini belirten bayrak. Yalnızca Word belgeleri için kullanılabilir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` olarak işaretlenmiş yalnızca imzaları döndürmek için bayrak. Varsayılan değer `False` olup, belirtilen kriterlere uyan tüm imzaların döndürüleceğini gösterir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
