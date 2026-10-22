---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Digital imza seçeneklerini temsil eder."
type: docs
weight: 1560
url: /tr/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Digital imza seçeneklerini temsil eder.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | DigitalSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | DigitalSignOptions sınıfının yeni bir örneğini sertifika akışıyla başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyasıyla başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | DigitalSignOptions sınıfının yeni bir örneğini sertifika akışı ve görüntü akışıyla başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | DigitalSignOptions sınıfının yeni bir örneğini sertifika akışı ve görüntü dosyasıyla başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyası ve görüntü akışıyla başlatır. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | DigitalSignOptions sınıfının yeni bir örneğini sertifika dosyası ve görüntü dosyasıyla başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Geçerlilik süresi sona ermiş bir sertifika ile imzalama yapılmasına izin veren bir bayrağı alır veya ayarlar. Varsayılan değer false'tur: süresi dolmuş bir sertifika ile imzalama [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception) hatasına neden olur ve belge imzalanmaz. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Geçerlilik süresi henüz başlamamış bir sertifika ile imzalama yapılmasına izin veren bir bayrağı alır veya ayarlar. Varsayılan değer false'tur: böyle bir sertifika ile imzalama [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception) hatasına neden olur ve belge imzalanmaz. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | İmzayı tüm belge sayfalarına yerleştir. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Kenarlık ayarlarını belirt. |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Dijital sertifika dosya yolunu alır veya ayarlar. Bu özellik yalnızca CertificateStream belirtilmemişse kullanılır. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Dijital sertifika akışını alır veya ayarlar. Bu özellik belirtilirse her zaman CertificateFilePath yerine kullanılır. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | İmza iletişim bilgisini alır veya ayarlar. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Kullanıcıların kendi dijital imzalama mantıklarını uygulamasına izin veren özel bir hash imzalama işlevini alır veya ayarlar. Bu, dış sertifikalarla imzalamayı etkinleştirir ve farklı hash algoritmalarını destekler. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alır veya ayarlar [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Kriptografik işlemler için kullanılacak hash algoritmasını alır veya ayarlar. Yalnızca PDF dosyalarındaki dijital imzalar için desteklenir. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Belge Sayfasındaki İmzanın Yüksekliği, ölçü değerlerinde (piksel, yüzde veya milimetre, bkz. [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Belge sayfasındaki imzanın yatay hizalaması. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | İmza görüntüsü dosya yolunu alır veya ayarlar. Bu özellik yalnızca ImageStream belirtilmemişse kullanılır. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | İmza görüntüsü akışını alır veya ayarlar. Bu özellik belirtilirse, her zaman ImageFilePath yerine kullanılır. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Belge sayfasındaki İmzanın sol X konumu, ölçü değerlerinde (piksel, yüzde veya milimetre; [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType bakınız). (yatay hizalama belirtilmemişse çalışır). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | İmza konumunu alır veya ayarlar. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikleri için ölçüm tipi (piksel, yüzde veya milimetre). |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilmişse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Kenar boşluğu için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmzalama için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1'dir. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Dijital sertifikanın şifresini alır veya ayarlar. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | İmzanın nedenini alır veya ayarlar. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Belgeye görüntünün yerleştirileceği alanın dikdörtgeni. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Belge sayfasındaki imzanın dönüş açısı (saat yönünde). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Şeklin belge düzeninde nerede sunulacağını tanımlar. Yalnızca Word belgeleri için kullanılabilir. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Belge dijital imzasının özelliklerini alır veya ayarlar. Pdf belgelerini imzalamak için gelişmiş özellikleri [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) örneği kullanarak ayarlamak mümkündür. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | İmza Tipini al [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Genişlik ve Yükseklik özellikleri için ölçü türü (piksel, yüzde veya milimetre). |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Belge Sayfası üzerindeki germe modu. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Belge sayfasındaki İmzanın üst Y konumu, ölçü değerlerinde (piksel, yüzde veya milimetre; [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType bakınız). (dikey hizalama belirtilmemişse çalışır). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | İmza şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında). Varsayılan değer 0 (opak)dır. |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | ltv (Long Term Validation) doğrulama bayrağını alır/ayarlar. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Belge sayfasındaki imzanın dikey hizalaması. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | İmzanın görünürlüğünü alır veya ayarlar. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Belge sayfasındaki İmzanın genişliği, ölçü değerlerinde (piksel, yüzde veya milimetre [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES türü [`XAdESType`](./xadestype). Varsayılan değer None (XAdES kapalı). Şu anda XAdES imza türü yalnızca Spreadsheet belgeleri için destekleniyor. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Metin imzasının Z-sıra konumunu alır veya ayarlar. Üst üste gelen imzaların görüntülenme sırasını belirler. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Dahili kaynakları temizler |

### Açıklamalar

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Ayrıca Bakınız

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
