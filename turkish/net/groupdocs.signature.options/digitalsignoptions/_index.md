---
title: DigitalSignOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Dijital imza seçeneklerini temsil eder.
type: docs
weight: 1340
url: /tr/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Dijital imza seçeneklerini temsil eder.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | DigitalSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Sertifika akışıyla DigitalSignOptions sınıfının yeni bir örneğini başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Sertifika dosyasıyla DigitalSignOptions sınıfının yeni bir örneğini başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Sertifika akışı ve görüntü akışı ile DigitalSignOptions sınıfının yeni bir örneğini başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Sertifika akışı ve görüntü dosyasıyla DigitalSignOptions sınıfının yeni bir örneğini başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Sertifika dosyası ve görüntü akışı ile DigitalSignOptions sınıfının yeni bir örneğini başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Sertifika dosyası ve resim dosyasıyla DigitalSignOptions sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Tüm belge sayfalarına imza koy. Bu özellik yalnızca çok çerçeveli görüntü biçimleri (Tiff) için kullanılabilir. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Sınır ayarlarını belirtin |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Dijital sertifika dosyası yolunu alır veya ayarlar. Bu özellik yalnızca CertificateStream belirtilmemişse kullanılır. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Dijital sertifika akışını alır veya ayarlar. Bu özellik belirtilirse, her zaman yerine CertificateFilePath. kullanılır. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | İmza kişisini alır veya ayarlar. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alın veya ayarlayın[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Yüksekliği (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Belge sayfasında yatay imza hizalaması. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | İmza görüntü dosyası yolunu alır veya ayarlar. Bu özellik yalnızca ImageStream belirtilmemişse kullanılır. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | İmza görüntü akışını alır veya ayarlar. Bu özellik belirtilirse, her zaman bunun yerine ImageFilePath. kullanılır. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Ölçü değerlerinde Belge Sayfasında İmzanın Sol X konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (yatay hizalama belirtilmemişse çalışır). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | İmza konumunu alır veya ayarlar. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikler için ölçüm türü (piksel, yüzde veya milimetre). |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | İşaret ve Belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilirse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Kenar Boşluğu için hesaplama türünü (piksel, yüzde veya milimetre) alır veya ayarlar. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmza için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1. 'dir. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Dijital sertifikanın parolasını alır veya ayarlar. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | İmza nedenini alır veya ayarlar. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Görüntüyü belgeye yerleştirmek için alanın dikdörtgeni. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Belge sayfasında imzanın dönüş açısı (saat yönünde). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Belge dijital imzasının özelliklerini alır veya ayarlar. Pdf belgelerini imzalamak için, örneğini kullanarak gelişmiş özellikleri ayarlamak mümkündür.[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | İmza Türünü Alın[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Genişlik ve Yükseklik özellikleri için ölçü türü (piksel, yüzde veya milimetre). |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Belge Sayfasında Uzatma modu. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Ölçüm değerlerinde Belge Sayfasındaki İmzanın Üst Y Konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (dikey hizalama belirtilmemişse çalışır). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | İmza saydamlığını alır veya ayarlar (0,0 (opak) ile 1,0 (temiz) arasındaki değer). Varsayılan değer 0'dır (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Belge sayfasında dikey imza hizalaması. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | İmzanın görünürlüğünü alır veya ayarlar. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Genişliği (piksel, yüzde veya milimetre)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES türü[`XAdESType`](./xadestype) . Varsayılan değer Yok'tur (XAdES kapalıdır). Şu anda XAdES imza türü yalnızca Elektronik Tablo belgeleri için desteklenmektedir. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Metin imzasının Z sırası konumunu alır veya ayarlar. Çakışan imzaların görüntülenme sırasını belirler. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Dahili kaynakları temizler |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Signature tarafından Dijital elektronik imza oluşturmanın temel kullanımı: [Dijital imza ile belge nasıl e-Sign edilir](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* GroupDocs.Signature ile Dijital elektronik imza ayarlarının gelişmiş kullanımı: [Dijital imza ve ek ayarlarla eSign belgesine gelişmiş kullanım](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Ayrıca bakınız

* class [ImageSignOptions](../imagesignoptions)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
