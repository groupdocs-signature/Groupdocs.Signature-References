---
title: "DigitalSignature"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Dijital imza özelliklerini içerir."
type: docs
weight: 150
url: /tr/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Dijital imza özelliklerini içerir.

```csharp
public class DigitalSignature : BaseSignature
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Dijital imzayı varsayılan parametrelerle başlat. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Dijital imzayı bilinen SignatureId ile başlat. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Belirtilen sertifika ile Dijital imza oluştur. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Belirtilen X509 deposuna dayanarak Dijital imza oluştur. Belirtilen depodaki ilk sertifika kullanılacak. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Belirtilen X509 Deposu ve sertifika indeksi temelinde Dijital imza oluştur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 sertifikasını alır veya ayarlar. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Sertifikanın özel mağaza adını belirtir. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Sertifikanın mağaza konumunu belirtir. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Sertifikanın mağaza adını belirtir. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | İmzalama amacı yorumunu alır veya ayarlar. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | İmza oluşturma tarihini al veya ayarla. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Bu imzanın belgelerden silinip silinmediğini gösteren bayrağı al. Bu özellik yalnızca silinen imzaların listesini tutmak için belge geçmişi günlük kayıtlarında kullanılır. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | İmzanın yüksekliğini belirtir. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu gösteren bayrağı al veya ayarla. Bu özellik, öğeyi imza (true) ya da belge öğesi (false) olarak ayarlamak için Update yöntemiyle kullanılır. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Bu dijital imza geçerli ve belgeye müdahale edilmemişse true değerini tutar. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | İmzanın sol konumunu belirtir. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | İmza değiştirme tarihini al veya ayarla. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | İmzanın bulunduğu sayfayı belirtir. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Güncelleme veya Silme yöntemleriyle belgede imzayı değiştirmek için benzersiz imza tanımlayıcısı. Bu özellik, Sign veya Search yöntemi çağrıldıktan sonra otomatik olarak ayarlanır. Bu özellik daha önce kaydedildiyse, imzayı manipüle etmek için manuel olarak ayarlanabilir. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | İmzanın türünü belirtir. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Belgenin imzalandığı zamanı alır veya ayarlar. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Bir sertifikanın parmak izini alır. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | İmzanın üst konumunu belirtir. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | İmzanın genişliğini belirtir. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES türü [`XAdESType`](./xadestype). Varsayılan değer None (XAdES kapalı). Şu anda XAdES imza türü yalnızca Spreadsheet belgeleri için destekleniyor. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Barkod İmza örneğini kopyalayın. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | GetHashCode metodunu geçersiz kılar |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Dijital imzaları tüm sistem X509 Sertifika Depolarından yükle. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Bir sertifika deposundan Dijital imzaları yükle. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Bir sertifika deposundan Dijital imzaları yükle. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Belirli bir konuma yerleştirilmiş dijital sertifika deposundan Dijital imzaları yükle. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Belirli bir konuma yerleştirilmiş dijital sertifika deposundan Dijital imzaları yükle. |

### Ayrıca Bakınız

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
