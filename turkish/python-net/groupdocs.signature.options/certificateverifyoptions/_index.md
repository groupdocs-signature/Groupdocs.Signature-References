---
title: "CertificateVerifyOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Sertifika belgelerini doğrulamak için seçenekleri tutar."
type: docs
url: /tr/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Sertifika belgelerini doğrulamak için seçenekleri tutar.

Daha fazla bilgi edinin

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

CertificateVerifyOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | TextVerifyOptions'ın yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Doğrulanacak konu ile yeni bir CertificateVerifyOptions örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | Bu özellik, doğrulama sonucuna göre sertifikanın süresi dolmuş olup olmadığını gösterir. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | Doğrulanacak sertifika yayıncısı. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | Doğrulama için kullanılan metin eşleşme türü. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | Doğrulama süreci, temel doğrulama politikası kullanılarak X.509 zincir doğrulaması sağlamalıdır. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | Doğrulanacak sertifikanın seri numarası. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | Doğrulanacak sertifika konusu. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | Doğrulanacak sertifika parmak izi. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Her belge sayfasının doğrulanıp doğrulanmayacağını gösteren bayrak. Varsayılan değer True'tir. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Alternatif imza seçenekleri doğrulaması için ek uzantılar. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Geçerli özellik bayrağı. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Doğrulanacak belge sayfa numarası; ayarlanmazsa, belgenin tüm sayfaları ilk oluşum için doğrulanır (minimum değer 1'dir). ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Doğrulanacak sayfaları belirtmek için sayfa seçenekleri. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Üstbilgi/altbilgi imzalarını doğrulamak için belge düzenindeki şekil konumu. ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) üzerinden devralınmıştır) |

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
