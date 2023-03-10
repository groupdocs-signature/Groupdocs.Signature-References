---
title: DigitalSignature
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Dijital imza özelliklerini içerir.
type: docs
weight: 150
url: /tr/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Dijital imza özelliklerini içerir.

```csharp
public class DigitalSignature : BaseSignature
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Dijital imzayı varsayılan parametrelerle başlatın. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Bilinen SignatureId. ile Dijital imzayı başlat |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Belirtilen sertifikayla Dijital imza oluşturun. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Belirtilen X509 deposuna dayalı olarak Dijital imza oluşturun. Belirtilen mağazadan alınan ilk sertifika kullanılacak. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Belirtilen X509 Mağazasına ve sertifika dizinine dayalı olarak Dijital imza oluşturun. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 sertifikasını alır veya ayarlar. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Sertifikanın depolama konumunu belirtir |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Sertifikanın mağaza adını belirtir. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | İmzalama amacı yorumunu alır veya ayarlar. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | İmza oluşturma tarihini alın veya ayarlayın. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Bu imzanın belgeden silinip silinmediğini gösteren bayrağı alın. Bu özellik, silinen imzaların listesini tutmak için yalnızca belge geçmişi günlük kayıtları için kullanılır. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | İmzanın yüksekliğini belirtir. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu belirtmek için işaret alın veya ayarlayın. Bu özellik, öğeyi imza (doğru) veya belge öğesi (yanlış) olarak ayarlamak için Update yöntemiyle birlikte kullanılıyor. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Bu dijital imza geçerliyse ve belge kurcalanmadıysa doğru kalır. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | İmzanın sol konumunu belirtir. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | İmza değiştirme tarihini alın veya ayarlayın. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | . üzerinde bulunan sayfa imzasını belirtir |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Belgedeki imzayı Güncelleme veya Silme yöntemleri üzerinden değiştirmek için benzersiz imza tanımlayıcı. Bu özellik, İmzalama veya Arama yöntemi çağrıldıktan sonra otomatik olarak ayarlanacaktır. Bu özellik, imzayı değiştirmek için manuel olarak ayarlanmadan önce kaydedilmişse. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | İmza türünü belirtir. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Belgenin imzalandığı zamanı alır veya ayarlar. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Bir sertifikanın parmak izini alır. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | İmzanın en üst konumunu belirtir. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | İmza genişliğini belirtir. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES türü[`XAdESType`](./xadestype) . Varsayılan değer Yok'tur (XAdES kapalıdır). Şu anda XAdES imza türü yalnızca Elektronik Tablo belgeleri için desteklenmektedir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Kopya Barkod İmza örneği. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | İmza özelliklerini karşılaştırmak için Equals yönteminin üzerine yazar |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | GetHashCode yöntemini geçersiz kılar |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Tüm sistem X509 Sertifika Mağazalarından Dijital imza yükleyin. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Geçilen X509 Sertifika Deposundan Dijital imza yükleyin. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Geçilen X509 Sertifika Deposundan Dijital imza yükleyin. |

### Ayrıca bakınız

* class [BaseSignature](../basesignature)
* ad alanı [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
