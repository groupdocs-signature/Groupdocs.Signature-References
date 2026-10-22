---
title: "TextSignOptions"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Metin imza seçeneklerini temsil eder."
type: docs
weight: 2020
url: /tr/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

Metin imza seçeneklerini temsil eder.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | TextSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | TextSignOptions sınıfının yeni bir örneğini metinle başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | İmzayı tüm belge sayfalarına yerleştir. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | İmza arka plan ayarlarını alır veya ayarlar. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Kenarlık ayarlarını belirt. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alır veya ayarlar [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | İmzanın yazı tipini alır veya ayarlar. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | İmzanın ön rengini alır veya ayarlar. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Metin imzasının yerleştirileceği metin form alanının başlığını alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField ile kullanılabilir. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Metin imzasının yerleştirileceği form alanının tipini alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField ile kullanılabilir. Varsayılan değer AllTextTypes'tir. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Kriptografik işlemler için kullanılacak hash algoritmasını alır veya ayarlar. Yalnızca PDF dosyalarındaki dijital imzalar için desteklenir. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Belge Sayfasındaki İmzanın Yüksekliği, Ölçüm değerlerinde (piksel, yüzde veya milimetre; [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliğine bakın). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Belge sayfasındaki imzanın yatay hizalaması. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | İmzanın Belge Sayfasındaki Sol X konumu, Ölçü değerlerinde (piksel, yüzde veya milimetre, [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType özelliğine bakın). (yatay hizalama belirtilmemişse çalışır). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikleri için ölçüm tipi (piksel, yüzde veya milimetre). |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilmişse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Kenar boşluğu için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Yerel özniteliği alır veya ayarlar. Eğer ayarlanırsa belgeye özgü imzalar kullanılabilir. WordProcessing belgeleri için yerel metin filigranı, örneğin, normalden farklıdır. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmzalama için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1'dir. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
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

* Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### Ayrıca Bakınız

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
