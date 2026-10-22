---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Pdf Dijital imza özelliklerini içerir."
type: docs
weight: 840
url: /tr/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Pdf Dijital imza özelliklerini içerir.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Sertifika olmadan Pdf Dijital İmza başlatın. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Belirtilen sertifika ile Pdf Dijital imza oluşturun. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Belirtilen X509 mağazasına göre Pdf Dijital İmza başlatın. Belirtilen mağazadan ilk sertifika kullanılacaktır. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Belirtilen X509 Mağazası ve sertifika indeksi temelinde Pdf Dijital imza oluşturun. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 sertifikasını alır veya ayarlar. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Sertifikanın özel mağaza adını belirtir. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Sertifikanın mağaza konumunu belirtir. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Sertifikanın mağaza adını belirtir. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | İmzalama amacı yorumunu alır veya ayarlar. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | İmzalayan tarafından, alıcının imzayı doğrulamak için imzalayanla iletişime geçebilmesini sağlamak amacıyla sağlanan bilgi, ör. telefon numarası. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | İmza oluşturma tarihini al veya ayarla. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Bu imzanın belgelerden silinip silinmediğini gösteren bayrağı al. Bu özellik yalnızca silinen imzaların listesini tutmak için belge geçmişi günlük kayıtlarında kullanılır. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | İmzanın yüksekliğini belirtir. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu gösteren bayrağı al veya ayarla. Bu özellik, öğeyi imza (true) ya da belge öğesi (false) olarak ayarlamak için Update yöntemiyle kullanılır. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Bu dijital imza geçerli ve belgeye müdahale edilmemişse true değerini tutar. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | İmzanın sol konumunu belirtir. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | İmzalamanın CPU ana bilgisayar adı veya fiziksel konumu. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | İmza değiştirme tarihini al veya ayarla. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | İmzanın bulunduğu sayfayı belirtir. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | İmzalamanın nedeni, örneğin (I agreeРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı, Dijital olarak imzalanan kişi {[`ContactInfo`](./contactinfo)} Tarih: {Date} Neden: {[`Reason`](./reason)} Konum: {[`Location`](./location)} gibi önceden tanımlı bir görünüm formatına sahiptir. ShowProperties varsayılan olarak true'dur. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Güncelleme veya Silme yöntemleriyle belgede imzayı değiştirmek için benzersiz imza tanımlayıcısı. Bu özellik, Sign veya Search yöntemi çağrıldıktan sonra otomatik olarak ayarlanır. Bu özellik daha önce kaydedildiyse, imzayı manipüle etmek için manuel olarak ayarlanabilir. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | İmzanın türünü belirtir. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Belgenin imzalandığı zamanı alır veya ayarlar. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Bir sertifikanın parmak izini alır. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Pdf dijital imza için zaman damgası. Varsayılan değer null'dur. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | İmzanın üst konumunu belirtir. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Pdf dijital imzanın türü. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | İmzanın genişliğini belirtir. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES türü [`XAdESType`](../digitalsignature/xadestype). Varsayılan değer None (XAdES kapalı). Şu anda XAdES imza türü yalnızca Spreadsheet belgeleri için desteklenmektedir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Barkod İmza örneğini kopyalayın. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | GetHashCode metodunu geçersiz kılar |

### Ayrıca Bakınız

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
