---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Görüntü imza seçeneklerini temsil eder."
type: docs
weight: 1670
url: /tr/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Görüntü imza seçeneklerini temsil eder.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | ImageSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | ImageSignOptions sınıfının yeni bir örneğini görüntü akışıyla başlatır. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | ImageSignOptions sınıfının yeni bir örneğini görüntü dosyasıyla başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | İmzayı tüm belge sayfalarına yerleştir. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Kenarlık ayarlarını belirt. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alır veya ayarlar [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Kriptografik işlemler için kullanılacak hash algoritmasını alır veya ayarlar. Yalnızca PDF dosyalarındaki dijital imzalar için desteklenir. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Belge Sayfasındaki İmzanın Yüksekliği, ölçü değerlerinde (piksel, yüzde veya milimetre, bkz. [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Belge sayfasındaki imzanın yatay hizalaması. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | İmza görüntüsü dosya yolunu alır veya ayarlar. Bu özellik yalnızca ImageStream belirtilmemişse kullanılır. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | İmza görüntüsü akışını alır veya ayarlar. Bu özellik belirtilirse, her zaman ImageFilePath yerine kullanılır. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Belge sayfasındaki İmzanın sol X konumu, ölçü değerlerinde (piksel, yüzde veya milimetre; [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType bakınız). (yatay hizalama belirtilmemişse çalışır). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikleri için ölçüm tipi (piksel, yüzde veya milimetre). |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilmişse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Kenar boşluğu için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmzalama için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1'dir. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Belgeye görüntünün yerleştirileceği alanın dikdörtgeni. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Belge sayfasındaki imzanın dönüş açısı (saat yönünde). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Şeklin belge düzeninde nerede sunulacağını tanımlar. Yalnızca Word belgeleri için kullanılabilir. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | İmza Tipini al [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Genişlik ve Yükseklik özellikleri için ölçü türü (piksel, yüzde veya milimetre). |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Belge Sayfası üzerindeki germe modu. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Belge sayfasındaki İmzanın üst Y konumu, ölçü değerlerinde (piksel, yüzde veya milimetre; [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType bakınız). (dikey hizalama belirtilmemişse çalışır). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | İmza şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında). Varsayılan değer 0 (opak)dır. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Belge sayfasındaki imzanın dikey hizalaması. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Belge sayfasındaki İmzanın genişliği, ölçü değerlerinde (piksel, yüzde veya milimetre [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Metin imzasının Z-sıra konumunu alır veya ayarlar. Üst üste gelen imzaların görüntülenme sırasını belirler. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Base64'ten önceden tanımlı Görüntü ile ImageSignOptions sınıfının yeni bir örneğini oluşturur. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Dahili kaynakları temizler |

### Açıklamalar

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Ayrıca Bakınız

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
