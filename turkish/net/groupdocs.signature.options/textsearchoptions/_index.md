---
title: TextSearchOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Metin imzaları için arama seçeneklerini temsil eder.
type: docs
weight: 1640
url: /tr/net/groupdocs.signature.options/textsearchoptions/
---
## TextSearchOptions class

Metin imzaları için arama seçeneklerini temsil eder.

```csharp
public class TextSearchOptions : SearchOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextSearchOptions](textsearchoptions#constructor)() | Varsayılan değerlerle TextSearchOptions sınıfının yeni bir örneğini başlatır. |
| [TextSearchOptions](textsearchoptions#constructor_1)(string) | Metin değeriyle TextSearchOptions sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Her Belge sayfasında arama yapmak için işaretleyin. Varsayılan olarak bu değer true. olarak ayarlanmıştır. |
| [MatchType](../../groupdocs.signature.options/textsearchoptions/matchtype) { get; set; } | Metin eşleme türü aramasını alır veya ayarlar. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Arama için Belge sayfa numarasını alır veya ayarlar. Değer isteğe bağlıdır. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | İmza araması için sayfaları belirleme seçenekleri. |
| [SignatureImplementation](../../groupdocs.signature.options/textsearchoptions/signatureimplementation) { get; set; } | Aranacak metin imza uygulamasını belirtir. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için işaretleyin. Varsayılan olarak, belirtilen ölçütlerle eşleşen tüm imzaların döndürüleceğini belirten false değeridir. |
| [Text](../../groupdocs.signature.options/textsearchoptions/text) { get; set; } | Aramada eşleşecek imza metnini belirtir. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Signature tarafından Metin elektronik imza aramasının temel kullanımı: [ Bir belgedeki Metin imzalarını e-Arama](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
* GroupDocs.Signature ile Metin elektronik imza arama ayarlarının gelişmiş kullanımı: [Bir belgede eSearch Metin imzalarının gelişmiş kullanımı ve ek ayarlar](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

### Ayrıca bakınız

* class [SearchOptions](../searchoptions)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->