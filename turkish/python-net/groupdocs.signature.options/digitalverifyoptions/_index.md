---
title: "DigitalVerifyOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bir belgenin dijital imzasını doğrulamak için seçenekleri tutar."
type: docs
url: /tr/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Bir belgenin dijital imzasını doğrulamak için seçenekleri tutar.

Daha fazla bilgi edinin

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

DigitalVerifyOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | DigitalVerifyOptions örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | DigitalVerifyOptions örneğini verilen dijital sertifika dosya yolu ile başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | DigitalVerifyOptions örneğini verilen sertifika akışı ile başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | Sertifika dosya yolu ya da akışından elde edilen X509Certificate2 sertifikası. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Dijital sertifikanın dosya yolu. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | Dijital sertifikanın akışı. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | Doğrulanacak dijital imzanın yorumları. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Doğrulanacak imza iletişim bilgisi. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | Doğrulanacak sertifikanın veren adı. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | Doğrulanacak imza konumu. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | Gerekli ise dijital sertifikanın parolası. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | Doğrulanacak dijital imzanın nedeni. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | Doğrulanacak dijital imzanın tarih ve saat aralığının başlangıcı. None değeri yok sayılacaktır. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | Doğrulanacak dijital imzanın tarih ve saat aralığının sonu. Null değeri yok sayılacaktır. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | Doğrulanacak sertifikanın konu ayırt edici adı; doğrulama, imzanın konu adının bu büyük/küçük harfe duyarlı değeri içerip içermediğini veya eşit olup olmadığını kontrol eder. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Her belge sayfasının doğrulanıp doğrulanmayacağını gösteren bayrak. Varsayılan değer True'tir. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Alternatif imza seçenekleri doğrulaması için ek uzantılar. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Geçerli özellik bayrağı. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Doğrulanacak belge sayfa numarası; ayarlanmazsa, belgenin tüm sayfaları ilk oluşum için doğrulanır (minimum değer 1'dir). ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Doğrulanacak sayfaları belirtmek için sayfa seçenekleri. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Üstbilgi/altbilgi imzalarını doğrulamak için belge düzenindeki şekil konumu. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
