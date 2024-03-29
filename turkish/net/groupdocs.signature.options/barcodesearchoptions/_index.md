---
title: BarcodeSearchOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Barkod imzaları için arama seçeneklerini temsil eder.
type: docs
weight: 1250
url: /tr/net/groupdocs.signature.options/barcodesearchoptions/
---
## BarcodeSearchOptions class

Barkod imzaları için arama seçeneklerini temsil eder.

```csharp
public class BarcodeSearchOptions : SearchOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [BarcodeSearchOptions](barcodesearchoptions#constructor)() | Varsayılan değerlerle BarcodeSearchOptions sınıfının yeni bir örneğini başlatır. |
| [BarcodeSearchOptions](barcodesearchoptions#constructor_1)(BarcodeType) | Kodlama türü değeriyle BarcodeSearchOptions sınıfının yeni bir örneğini başlatır. |
| [BarcodeSearchOptions](barcodesearchoptions#constructor_2)(BarcodeType, string) | Kodlama türü ve metin değerleri ile BarcodeSearchOptions sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Her Belge sayfasında arama yapmak için işaretleyin. Varsayılan olarak bu değer true. olarak ayarlanmıştır. |
| [EncodeType](../../groupdocs.signature.options/barcodesearchoptions/encodetype) { get; set; } | Barkodları aramak için Encode Type özelliğini belirtir. Bu değer ayarlanmazsa, desteklenen tüm Barkod Türleri için arama yapılır |
| [MatchType](../../groupdocs.signature.options/barcodesearchoptions/matchtype) { get; set; } | Barkod metni Eşleme Türü aramasını alır veya ayarlar. Yalnızca Metin özelliği ayarlandığında kullanılır. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Arama için Belge sayfa numarasını alır veya ayarlar. Değer isteğe bağlıdır. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | İmza araması için sayfaları belirleme seçenekleri. |
| [ReturnContent](../../groupdocs.signature.options/barcodesearchoptions/returncontent) { get; set; } | Belge sayfasındaki imzanın Barkod görüntü içeriğini almak için işaret alır veya ayarlar. Bu işaret doğru olarak ayarlanırsa, Barkod imza görüntü içeriği ham görüntü verilerini gereken formatta tutar[`ReturnContentType`](./returncontenttype) . Varsayılan olarak bu seçenek devre dışıdır. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesearchoptions/returncontenttype) { get; set; } | ReturnContent özelliği etkinleştirildiğinde, Barkod imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. Varsayılan olarak Null olarak ayarlanmıştır. Bu, Barkod görüntü içeriğini orijinal biçimde döndürmek anlamına gelir. Bu resim formatı şu adreste belirtilmiştir:[`Format`](../../groupdocs.signature.domain/barcodesignature/format) Desteklenen olası değerler şunlardır: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan biçim desteklenmiyorsa, .png biçimindeki Barkod görüntü içeriği döndürülür. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için işaretleyin. Varsayılan olarak, belirtilen ölçütlerle eşleşen tüm imzaların döndürüleceğini belirten false değeridir. |
| [Text](../../groupdocs.signature.options/barcodesearchoptions/text) { get; set; } | Aranması ve eşleşmesi gerekiyorsa Barkod İmza metnini belirtir. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından Barkod elektronik imza aramanın temel kullanımı. İmza: [ Bir belgedeki Barkod imzalarını e-Arama](https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures)
* GroupDocs.Signature ile Barkod elektronik imza arama ayarlarının gelişmiş kullanımı: [Bir belgede eSearch Barkod imzalarının gelişmiş kullanımı ve ek ayarlar](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures)

### Ayrıca bakınız

* class [SearchOptions](../searchoptions)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
