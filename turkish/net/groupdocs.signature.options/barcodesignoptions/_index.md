---
title: BarcodeSignOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Barkod imza seçeneklerini temsil eder.
type: docs
weight: 1190
url: /tr/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Barkod imza seçeneklerini temsil eder.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | Varsayılan değerlerle BarcodeSignOptions sınıfının yeni bir örneğini başlatır. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | BarcodeSignOptions sınıfının yeni bir örneğini text. ile başlatır |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | BarcodeSignOptions sınıfının yeni bir örneğini text. ile başlatır |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Tüm belge sayfalarına imza koyun. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | İmza arka plan ayarlarını alır veya ayarlar. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Sınır ayarlarını belirtin |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Sonuç Barkod görüntüsündeki metnin hizalamasını alır veya ayarlar. Varsayılan değer Yok'tur. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alın veya ayarlayın[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Barkod türünü alır veya ayarlar. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | İmza yazı tipini alır veya ayarlar. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Barkodun Ön rengini alır veya ayarlar bars Bu özelliğin kullanılması, doğrulamada sorunlara neden olabilir. Dikkatli kullanın. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Metin imzası koymak için metin formu alanının başlığını alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField. ile kullanılabilir |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | İçine metin imzası koymak için form alanının türünü alır veya ayarlar. Bu özellik yalnızca SignatureImplementation ile kullanılabilir = TextToFormField. Değer varsayılan olarak AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Yüksekliği (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliği). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Belge sayfasında imzanın yatay hizalaması. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Barkod öğeleri ile sonuç görüntü kenarlıkları arasındaki boşluğu alır veya ayarlar. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Ölçü değerleri 'de Belge Sayfasında İmzanın Sol X konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType özelliği). (yatay hizalama belirtilmemişse çalışır). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikler için ölçüm türü (piksel, yüzde veya milimetre). |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | İşaret ve Belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilirse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Kenar Boşluğu için hesaplama türünü (piksel, yüzde veya milimetre) alır veya ayarlar. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Yerel özniteliği alır veya ayarlar. Ayarlanırsa, belgeye özel imzalar kullanılabilir. WordProcessing belgeleri için yerel metin filigranı normalden farklıdır, örneğin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmzalama için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | Belge sayfasına konulan bir imzanın Barkod görüntü içeriğini almak için bayrağı alır veya ayarlar. Bu bayrak doğru olarak ayarlanırsa, Barkod imza görüntü içeriği, ham görüntü verilerini gerekli formatta tutar[`ReturnContentType`](./returncontenttype) . Varsayılan olarak bu seçenek devre dışıdır. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | ReturnContent özelliği etkinleştirildiğinde, Barkod imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. Varsayılan olarak Null olarak ayarlanmıştır. Bu, Barkod görüntü içeriğini orijinal biçimde döndürmek anlamına gelir. Bu resim formatı şu adreste belirtilmiştir:[`Format`](../../groupdocs.signature.domain/barcodesignature/format) Desteklenen olası değerler şunlardır: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan biçim desteklenmiyorsa, .png biçimindeki Barkod görüntü içeriği döndürülür. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Belge sayfasında imzanın dönüş açısı (saat yönünde). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Metin koymak için şeklin türünü alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextStamp. ile kullanılabilir. Değer varsayılan olarak Rectangle'dır. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Benzersiz imza kimliğini alır veya ayarlar. İmza doğrulama seçeneklerinde kullanılabilir. Özellik yalnızca PDF belgeleri için desteklenir. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Metin imza uygulamasının türünü alır veya ayarlar. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | İmza Türünü Alın[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Genişlik ve Yükseklik özellikleri için ölçü türü (piksel, yüzde veya milimetre). |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Belge Sayfasında Uzatma modu. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | İmza metnini alır veya ayarlar. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | İmza içindeki metnin yatay olarak hizalanması. Bu özellik yalnızca Görüntü ve Ek Açıklama imza uygulamaları için desteklenir (bkz.[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation özelliği). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Bir imza içindeki metnin dikey hizalaması. Bu özellik yalnızca Resim imzası uygulaması için desteklenir (bkz.[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation özelliği). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Ölçü değerleri 'de Belge Sayfasında İmzanın Üst Y Konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType özelliği). (dikey hizalama belirtilmemişse çalışır). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | İmza saydamlığını alır veya ayarlar (0,0 (opak) ile 1,0 (temiz) arasındaki değer). Varsayılan değer 0'dır (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Belge sayfasında dikey imza hizalaması. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Genişliği (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliği). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Metin imzasının Z sırası konumunu alır veya ayarlar. Çakışan imzaların görüntülenme sırasını belirler. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Signature tarafından Barkod elektronik imza oluşturmanın temel kullanımı: [Barkod imzalı belge nasıl eSign edilir](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* GroupDocs.Signature ile Barkod elektronik imza ayarlarının gelişmiş kullanımı: [Barkod imzası ve ek ayarlarla belgeyi eSign için gelişmiş kullanım](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### Ayrıca bakınız

* class [TextSignOptions](../textsignoptions)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
