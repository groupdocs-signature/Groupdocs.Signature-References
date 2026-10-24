---
title: "PdfDigitalSignature sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "PDF dijital imza özelliklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

PDF dijital imza özelliklerini temsil eder.

PdfDigitalSignature türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | Bir PDF dijital imzasını sertifika olmadan başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | Belirtilen X509 mağazasını kullanarak bir PDF dijital imzasını başlatır. Mağazadan ilk sertifika kullanılacaktır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | Belirtilen X509 mağazası ve sertifika indeksi kullanılarak bir PDF dijital imzasını başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | Belirtilen X509 sertifikasıyla bir PDF dijital imzasını başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | PDF dijital imza örneğini kopyalar. |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | İmza özelliklerini karşılaştırarak eşitliği belirler. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | GetHashCode metodunu geçersiz kılar. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Tüm sistem X509 sertifika mağazalarından dijital imzaları yükler. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) 'dan miras alınmıştır) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) 'dan miras alınmıştır) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) 'dan miras alınmıştır) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) 'dan miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | İmzalayan tarafından, alıcının imzayı doğrulamasını sağlamak amacıyla sağlanan iletişim bilgileri, ör. bir telefon numarası. |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | İmzanın CPU ana bilgisayar adı veya fiziksel konumu. |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | İmzalanma nedeni, ör. (I agree). |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | İmza özelliklerinin gösterilmesini veya gizlenmesini zorlayan bayrak; true olduğunda, imza alanı önceden tanımlı bir görünüm formatı kullanır (ör., `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`) ve varsayılan olarak True olur. |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | PDF dijital imzası için zaman damgası. Varsayılan değer None'dur. |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | PDF dijital imzasının türü. |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Dijital imza ile ilişkili X509 sertifikası. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Sertifikanın özel mağaza adı. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Sertifikanın mağaza konumu. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Sertifikanın mağaza adı. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | İmza amacı yorumu. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | İmza oluşturma tarihi. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bu imzanın belgeden silinip silinmediğini gösteren bayrak. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | İmzanın yüksekliği. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bu bileşenin bir imza (`True`) mı yoksa belge içeriği (`False`) mı olduğunu gösteren bayrak. (kalıtım alınan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Dijital imza geçerlidir ve belge değiştirilmemiştir. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | İmzanın sol konumu. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | İmzanın değiştirilme tarihi. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | İmzanın bulunduğu sayfa numarası. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Belgenin imzalanma zamanı. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | İmzanın benzersiz tanımlayıcısı, güncelleme veya silme işlemleriyle belgede imzayı değiştirmek için kullanılır. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | İmza türü. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Bir sertifikanın parmak izi. ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | İmzanın üst konumu. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | İmzanın genişliği. ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) üzerinden devralınmıştır) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | XAdES türü ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). ([`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) üzerinden devralınmıştır) |

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
