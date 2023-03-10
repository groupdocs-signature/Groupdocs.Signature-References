---
title: QrCodeSignOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: QR Kodu imza seçeneklerini temsil eder.
type: docs
weight: 1630
url: /tr/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

QR Kodu imza seçeneklerini temsil eder.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Varsayılan değerlerle QRCodeSignOptions sınıfının yeni bir örneğini başlatır. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Metin ile QRCodeSignOptions sınıfının yeni bir örneğini başlatır. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | BarcodeSignOptions sınıfının yeni bir örneğini text. ile başlatır |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Tüm belge sayfalarına imza koyun. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | İmza arka plan ayarlarını alır veya ayarlar. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Sınır ayarlarını belirtin |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Sonuç QR kodu görüntüsündeki metnin hizalamasını alır veya ayarlar. Varsayılan değer Yok'tur. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | QR Kodu içeriğine seri hale getirmek için özel nesneyi alır veya ayarlar. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Şunun uygulanmasını alır veya ayarlar:[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) QR Kodu İmza Metni veya Veri özelliklerini kodlamak ve kodunu çözmek için arayüz. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alın veya ayarlayın[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | QR Kodu türünü alır veya ayarlar. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | İmza yazı tipini alır veya ayarlar. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | QR Kodunun Ön rengini alır veya ayarlar bars Bu özelliğin kullanılması, doğrulamada sorunlara neden olabilir. Dikkatli kullanın. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | İçine metin imzası koymak için metin formu alanının başlığını alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField. ile kullanılabilir |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Metin imzası koymak için form alanının türünü alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField. ile kullanılabilir. Varsayılan değer AllTextTypes. 'dir. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Yüksekliği (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliği). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Belge sayfasında yatay imza hizalaması. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | QR Kodu öğeleri ile sonuç görüntü kenarlıkları arasındaki boşluğu alır veya ayarlar. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Ölçü değerlerinde Belge Sayfasında İmzanın Sol X konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType özelliği). (yatay hizalama belirtilmemişse çalışır). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikler için ölçüm türü (piksel, yüzde veya milimetre). |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | QR kodu logo resim dosyası adını alır veya ayarlar. Bu özellik, yalnızca LogoStream belirtilmemişse kullanılır. Bu özelliğin kullanılması, doğrulamada sorunlara neden olabilir. Dikkatli kullanın. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | QR kodu logo görüntü akışını alır veya ayarlar. Bu özellik belirtilirse, her zaman bunun yerine LogoFilePath. Bu özelliğin kullanılması doğrulamada sorunlara neden olabilir. Dikkatli kullanın. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | İşaret ve Belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilirse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Kenar Boşluğu için hesaplama türünü (piksel, yüzde veya milimetre) alır veya ayarlar. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Yerel özniteliği alır veya ayarlar. Ayarlanırsa, belgeye özel imzalar kullanılabilir. WordProcessing belgeleri için yerel metin filigranı normalden farklıdır, örneğin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmza için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1. 'dir. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Belge sayfasına konulan bir imzanın QR-Code görüntü içeriğini almak için bayrağı alır veya ayarlar. Bu bayrak doğru olarak ayarlanırsa, QR-Code imza görüntü içeriği, ham görüntü verilerini gerekli formatta tutar[`ReturnContentType`](./returncontenttype) . Varsayılan olarak bu seçenek devre dışıdır. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | ReturnContent özelliği etkinleştirildiğinde QR Kodu imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. Varsayılan olarak Null olarak ayarlanmıştır. Bu, QR-Code görüntü içeriğini orijinal biçimde döndürmek anlamına gelir. Bu resim formatı şu adreste belirtilmiştir:[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) Desteklenen olası değerler şunlardır: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan biçim desteklenmiyorsa, .png biçimindeki QR-Code resim içeriği döndürülür. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Belge sayfasında imzanın dönüş açısı (saat yönünde). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Metin koymak için şeklin türünü alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextStamp. ile kullanılabilir. Değer varsayılan olarak Rectangle. 'dir. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Benzersiz imza kimliğini alır veya ayarlar. İmza doğrulama seçeneklerinde kullanılabilir. Özellik yalnızca PDF belgeleri için desteklenir. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Metin imza uygulamasının türünü alır veya ayarlar. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | İmza Türünü Alın[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Genişlik ve Yükseklik özellikleri için ölçü türü (piksel, yüzde veya milimetre). |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Belge Sayfasında Uzatma modu. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | İmza metnini alır veya ayarlar. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | İmza içindeki metnin yatay olarak hizalanması. Bu özellik yalnızca Görüntü ve Ek Açıklama imza uygulamaları için desteklenir (bkz.[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation özelliği). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | İmza içindeki metnin dikey hizalanması. Bu özellik yalnızca Görüntü imza uygulaması için desteklenir (bkz.[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation özelliği). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Ölçüm değerlerinde Belge Sayfasındaki İmzanın Üst Y Konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType özelliği). (dikey hizalama belirtilmemişse çalışır). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | İmza saydamlığını alır veya ayarlar (0,0 (opak) ile 1,0 (temiz) arasındaki değer). Varsayılan değer 0'dır (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Belge sayfasında dikey imza hizalaması. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Genişliği (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliği). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Metin imzasının Z sırası konumunu alır veya ayarlar. Çakışan imzaların görüntülenme sırasını belirler. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Signature tarafından QR Kodu elektronik imza oluşturmanın temel kullanımı: [Belgeyi QR-Code imzasıyla e-Sign nasıl yapılır](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* GroupDocs.Signature ile QR-Code elektronik imza ayarlarının gelişmiş kullanımı: [QR-Code imzası ve ek ayarlarla eSign belgesine gelişmiş kullanım](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Ayrıca bakınız

* class [TextSignOptions](../textsignoptions)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
