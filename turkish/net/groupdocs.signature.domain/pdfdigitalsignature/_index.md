---
title: PdfDigitalSignature
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Pdf Dijital imza özelliklerini içerir.
type: docs
weight: 630
url: /tr/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Pdf Dijital imza özelliklerini içerir.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Pdf Dijital İmzayı sertifikasız olarak başlatın. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Belirtilen sertifikayla PDF Dijital imzası oluşturun. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Belirtilen X509 deposuna dayalı olarak Pdf Dijital İmzayı başlatın. Belirtilen mağazadan alınan ilk sertifika kullanılacak. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Belirtilen X509 Mağazasına ve sertifika dizinine dayalı olarak Pdf Dijital imzası oluşturun. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 sertifikasını alır veya ayarlar. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Sertifikanın depolama konumunu belirtir |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Sertifikanın mağaza adını belirtir. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | İmzalama amacı yorumunu alır veya ayarlar. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Bir alıcının imzayı doğrulamak için imzalayanla iletişim kurmasını sağlamak için imzalayan tarafından sağlanan bilgiler, örneğin bir telefon numarası. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | İmza oluşturma tarihini alın veya ayarlayın. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Bu imzanın belgeden silinip silinmediğini gösteren bayrağı alın. Bu özellik, silinen imzaların listesini tutmak için yalnızca belge geçmişi günlük kayıtları için kullanılır. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | İmzanın yüksekliğini belirtir. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu belirtmek için işaret alın veya ayarlayın. Bu özellik, öğeyi imza (doğru) veya belge öğesi (yanlış) olarak ayarlamak için Update yöntemiyle birlikte kullanılıyor. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Bu dijital imza geçerliyse ve belge kurcalanmadıysa doğru kalır. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | İmzanın sol konumunu belirtir. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | İmzalamanın CPU ana bilgisayar adı veya fiziksel konumu. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | İmza değiştirme tarihini alın veya ayarlayın. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | . üzerinde bulunan sayfa imzasını belirtir |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | İmzalama nedeni, örneğin (Kabul ediyorumРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | İmza özelliklerini göstermeye/gizlemeye zorla. ShowProperties'in true olması durumunda,signage alanı önceden tanımlanmış görünüm biçimine sahiptir Dijital olarak { tarafından imzalanmıştır[`ContactInfo`](./contactinfo)} Tarih: {Tarih} Neden: {[`Reason`](./reason)_ Konum: {[`Location`](./location) _ ShowProperties varsayılan olarak doğrudur. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Belgedeki imzayı Güncelleme veya Silme yöntemleri üzerinden değiştirmek için benzersiz imza tanımlayıcı. Bu özellik, İmzalama veya Arama yöntemi çağrıldıktan sonra otomatik olarak ayarlanacaktır. Bu özellik, imzayı değiştirmek için manuel olarak ayarlanmadan önce kaydedilmişse. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | İmza türünü belirtir. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Belgenin imzalandığı zamanı alır veya ayarlar. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Bir sertifikanın parmak izini alır. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Pdf dijital imzası için zaman damgası. Varsayılan değer boştur. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | İmzanın en üst konumunu belirtir. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Pdf dijital imza türü. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | İmza genişliğini belirtir. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES türü[`XAdESType`](../digitalsignature/xadestype) . Varsayılan değer Yok'tur (XAdES kapalıdır). Şu anda XAdES imza türü yalnızca Elektronik Tablo belgeleri için desteklenmektedir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Kopya Barkod İmza örneği. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | İmza özelliklerini karşılaştırmak için Equals yönteminin üzerine yazar |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | GetHashCode yöntemini geçersiz kılar |

### Ayrıca bakınız

* class [DigitalSignature](../digitalsignature)
* ad alanı [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
