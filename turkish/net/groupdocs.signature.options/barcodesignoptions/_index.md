---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Barcode imza seçeneklerini temsil eder."
type: docs
weight: 1450
url: /tr/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Barcode imza seçeneklerini temsil eder.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | BarcodeSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | BarcodeSignOptions sınıfının yeni bir örneğini metinle başlatır. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | BarcodeSignOptions sınıfının yeni bir örneğini metinle başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | İmzayı tüm belge sayfalarına yerleştir. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | İmza arka plan ayarlarını alır veya ayarlar. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Kenarlık ayarlarını belirt. |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Sonuç Barcode görüntüsündeki metnin hizalamasını alır veya ayarlar. Varsayılan değer None'dur. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alır veya ayarlar [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Barcode tipini alır veya ayarlar. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | İmzanın yazı tipini alır veya ayarlar. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Barcode çubuklarının Ön renk değerini alır veya ayarlar. Bu özelliğin kullanımı doğrulama sorunlarına yol açabilir. Dikkatli kullanın. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Metin imzasının yerleştirileceği metin form alanının başlığını alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField ile kullanılabilir. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Metin imzasının yerleştirileceği form alanının tipini alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField ile kullanılabilir. Varsayılan değer AllTextTypes'tir. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Kriptografik işlemler için kullanılacak hash algoritmasını alır veya ayarlar. Yalnızca PDF dosyalarındaki dijital imzalar için desteklenir. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Belge Sayfasındaki İmzanın Yüksekliği, Ölçüm değerlerinde (piksel, yüzde veya milimetre; [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliğine bakın). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Belge sayfasındaki imzanın yatay hizalaması. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Barcode öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | İmzanın Belge Sayfasındaki Sol X konumu, Ölçü değerlerinde (piksel, yüzde veya milimetre, [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType özelliğine bakın). (yatay hizalama belirtilmemişse çalışır). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikleri için ölçüm tipi (piksel, yüzde veya milimetre). |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilmişse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Kenar boşluğu için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Yerel özniteliği alır veya ayarlar. Eğer ayarlanırsa belgeye özgü imzalar kullanılabilir. WordProcessing belgeleri için yerel metin filigranı, örneğin, normalden farklıdır. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmzalama için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1'dir. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | İmzanın belge sayfasına yerleştirilen Barcode görüntü içeriğini almak için bayrağı alır veya ayarlar. Bu bayrak true olarak ayarlanırsa, Barcode imza görüntü içeriği, gerekli formatta [`ReturnContentType`](./returncontenttype) tarafından ham görüntü verisini tutacaktır. Varsayılan olarak bu seçenek devre dışıdır. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | ReturnContent özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. Varsayılan olarak Null olarak ayarlanır. Bu, Barcode görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir. Bu görüntü formatı [`Format`](../../groupdocs.signature.domain/barcodesignature/format) adresinde belirtilir. Desteklenen olası değerler: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan format desteklenmiyorsa Barcode görüntü içeriği .png formatında döndürülecektir. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Belge sayfasındaki imzanın dönüş açısı (saat yönünde). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Şeklin belge düzeninde nerede sunulacağını tanımlar. Yalnızca Word belgeleri için kullanılabilir. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Metni yerleştirmek için şekil tipini alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextStamp ile kullanılabilir. Varsayılan değer Rectangle'tır. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | İmzanın benzersiz kimliğini alır veya ayarlar. İmza doğrulama seçeneklerinde kullanılabilir. Özellik yalnızca Pdf belgeleri için desteklenir. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Metin imza uygulamasının tipini alır veya ayarlar. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | İmza Tipini al [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Genişlik ve Yükseklik özellikleri için ölçü türü (piksel, yüzde veya milimetre). |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Belge Sayfası üzerindeki germe modu. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | İmzanın metnini alır veya ayarlar. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | İmza içindeki metnin yatay hizalaması. Bu özellik yalnızca Image ve Annotation imza uygulamaları için desteklenir (bkz. [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation özelliği). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | İmza içindeki metnin dikey hizalaması. Bu özellik yalnızca Image imza uygulaması için desteklenir (bkz. [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation özelliği). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | İmzanın Belge Sayfasındaki Üst Y konumu, Ölçü değerlerinde (piksel, yüzde veya milimetre, [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliğine bakın). (dikey hizalama belirtilmemişse çalışır). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | İmza şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında). Varsayılan değer 0 (opak)dır. |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Belge sayfasındaki imzanın dikey hizalaması. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | İmzanın Belge Sayfasındaki Genişliği, Ölçü değerlerinde (piksel, yüzde veya milimetre, [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliğine bakın). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Metin imzasının Z-sıra konumunu alır veya ayarlar. Üst üste gelen imzaların görüntülenme sırasını belirler. |

### Açıklamalar

**Learn more**

* Basic usage of creating Barcode electronic signature by GroupDocs.Signature: [How to eSign document with Barcode signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Barcode signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### Ayrıca Bakınız

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
