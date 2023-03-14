---
title: TextSignOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Metin imza seçeneklerini temsil eder.
type: docs
weight: 1730
url: /tr/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

Metin imza seçeneklerini temsil eder.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | Varsayılan değerlerle TextSignOptions sınıfının yeni bir örneğini başlatır. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | Text. ile TextSignOptions sınıfının yeni bir örneğini başlatır |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Tüm belge sayfalarına imza koyun. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Ek imza görünümü. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | İmza arka plan ayarlarını alır veya ayarlar. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Sınır ayarlarını belirtin |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | İmza Seçeneklerinin Belge Türünü alın veya ayarlayın[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | İmza Uzantıları. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | İmza yazı tipini alır veya ayarlar. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | İmzanın ön rengini alır veya ayarlar. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | İçine metin imzası koymak için metin formu alanının başlığını alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField. ile kullanılabilir |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Metin imzası koymak için form alanının türünü alır veya ayarlar. Bu özellik yalnızca SignatureImplementation = TextToFormField. ile kullanılabilir. Varsayılan değer AllTextTypes. 'dir. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Ölçü değerlerinde Belge Sayfasındaki İmza Yüksekliği (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType özelliği). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Belge sayfasında yatay imza hizalaması. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Ölçü değerlerinde Belge Sayfasında İmzanın Sol X konumu (piksel, yüzde veya milimetre bkz.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType özelliği). (yatay hizalama belirtilmemişse çalışır). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Sol ve Üst özellikler için ölçüm türü (piksel, yüzde veya milimetre). |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | İşaret ve Belge kenarları arasındaki boşluğu alır veya ayarlar. (YALNIZCA yatay veya dikey hizalama belirtilirse çalışır). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Kenar Boşluğu için hesaplama türünü (piksel, yüzde veya milimetre) alır veya ayarlar. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Yerel özniteliği alır veya ayarlar. Ayarlanırsa, belgeye özel imzalar kullanılabilir. WordProcessing belgeleri için yerel metin filigranı normalden farklıdır, örneğin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | İmza için belge sayfa numarasını alır veya ayarlar. Minimum ve varsayılan değer 1. 'dir. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
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

* GroupDocs.Signature tarafından Metin elektronik imza oluşturmanın temel kullanımı: [Belgeyi Metin imzasıyla e-İmzalama](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* GroupDocs.Signature ile Metin elektronik imza ayarlarının gelişmiş kullanımı: [Metin imzası ve ek ayarlarla eSign belgesine gelişmiş kullanım](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### Ayrıca bakınız

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
