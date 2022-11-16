---
title: StampSignOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Damga imzası seçeneklerini temsil eder.
type: docs
weight: 1630
url: /tr/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Damga imzası seçeneklerini temsil eder.

```csharp
public class StampSignOptions : ImageSignOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Varsayılan değerlerle StampSignOptions sınıfının yeni bir örneğini başlatır. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Hizalama seçenekleriyle StampSignOptions sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Tüm belge sayfalarına imza koyun. Bu özellik yalnızca çok kareli görüntü biçimleri (Tiff) için kullanılabilir. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Damga arka planını alır veya ayarlar. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | İmzanın arka plan rengi kırpma türünü alır veya ayarlar. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Arka plan resmi kırpma imza türünü alır veya ayarlar. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Sınır ayarlarını belirtin |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alın veya ayarlayın[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Yüksekliği (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Belge sayfasında imzanın yatay hizalaması. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | İmza resim dosyası yolunu alır veya ayarlar. Bu özellik yalnızca ImageStream belirtilmemişse kullanılır. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | İmza görüntü akışını alır veya ayarlar. Bu özellik belirtilirse, bunun yerine her zaman kullanılır ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Dikdörtgenler kümesi olarak işlenen İç Çizgilerin Listesi. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Ölçü değerleri 'de Belge Sayfasında İmzanın Sol X konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (yatay hizalama belirtilmemişse çalışır). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikler için ölçüm türü (piksel, yüzde veya milimetre). |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | İşaret ve Belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilirse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Kenar Boşluğu için hesaplama türünü (piksel, yüzde veya milimetre) alır veya ayarlar. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Eşmerkezli daireler olarak işlenen Dış Çizgilerin Listesi. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmzalama için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Görüntüyü belgeye yerleştirmek için alanın dikdörtgeni. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Belge sayfasında imzanın dönüş açısı (saat yönünde). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | İmza Türünü Alın[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Genişlik ve Yükseklik özellikleri için ölçü türü (piksel, yüzde veya milimetre). |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Damga türünü alır veya ayarlar. Varsayılan değer Round'dur. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Belge Sayfasında Uzatma modu. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Ölçü değerleri 'de Belge Sayfasında İmzanın Üst Y Konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (dikey hizalama belirtilmemişse çalışır). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | İmza saydamlığını alır veya ayarlar (0,0 (opak) ile 1,0 (temiz) arasındaki değer). Varsayılan değer 0'dır (opak). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Belge sayfasında dikey imza hizalaması. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Genişliği (piksel, yüzde veya milimetre)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Metin imzasının Z sırası konumunu alır veya ayarlar. Çakışan imzaların görüntülenme sırasını belirler. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Dahili kaynakları temizler |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından Damga elektronik imzası oluşturmanın temel kullanımı.İmza: [Damga imzalı belge nasıl e-Sign edilir](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* GroupDocs.Signature ile Damga elektronik imza ayarlarının gelişmiş kullanımı: [Damga imzası ve ek ayarlarla belgeyi eSign için gelişmiş kullanım](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Ayrıca bakınız

* class [ImageSignOptions](../imagesignoptions)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
