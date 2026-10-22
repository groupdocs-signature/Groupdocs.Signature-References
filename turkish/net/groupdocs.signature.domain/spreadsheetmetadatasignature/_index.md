---
title: "SpreadsheetMetadataSignature"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Spreadsheet Meta Verisi İmza özelliklerini içerir."
type: docs
weight: 1060
url: /tr/net/groupdocs.signature.domain/spreadsheetmetadatasignature/
---
## SpreadsheetMetadataSignature class

Spreadsheet Meta Verisi İmza özelliklerini içerir.

```csharp
public sealed class SpreadsheetMetadataSignature : MetadataSignature
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor)(string) | Önceden tanımlı ad ve boş değerle Spreadsheet Metadata Signature oluşturur. |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor_1)(string, object) | Önceden tanımlı değerlerle Spreadsheet Metadata Signature oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | İmza oluşturma tarihini al veya ayarla. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | İmza Değer özelliklerini kodlamak ve çözmek için [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Bu imzanın belgelerden silinip silinmediğini gösteren bayrağı al. Bu özellik yalnızca silinen imzaların listesini tutmak için belge geçmişi günlük kayıtlarında kullanılır. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | İmzanın yüksekliğini belirtir. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu gösteren bayrağı al veya ayarla. Bu özellik, öğeyi imza (true) ya da belge öğesi (false) olarak ayarlamak için Update yöntemiyle kullanılır. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | İmzanın sol konumunu belirtir. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | İmza değiştirme tarihini al veya ayarla. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Benzersiz meta veri adını belirtir. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | İmzanın bulunduğu sayfayı belirtir. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Güncelleme veya Silme yöntemleriyle belgede imzayı değiştirmek için benzersiz imza tanımlayıcısı. Bu özellik, Sign veya Search yöntemi çağrıldıktan sonra otomatik olarak ayarlanır. Bu özellik daha önce kaydedildiyse, imzayı manipüle etmek için manuel olarak ayarlanabilir. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | İmzanın türünü belirtir. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | İmzanın üst konumunu belirtir. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Meta veri değer tipini belirtir. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Meta veri nesnesini belirtir. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | İmzanın genişliğini belirtir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone_1)() | Meta Veri İmzası örneğini kopyalar. |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone)(object) | Verilen değerle Spreadsheet Metadata Signature örneğini kopyalar. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Serileştirme sonrası Meta Veri İmza Değerinden nesne elde eder. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Serileştirme sonrası Meta Veri İmza Metninden nesne elde eder. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | GetHashCode metodunu geçersiz kılar |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Boolean değere dönüştürür |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | DateTime'a dönüştürür. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | DateTime'a dönüştürür. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Decimal'a dönüştürür. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Decimal'a dönüştürür. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Double'a dönüştürür. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Double'a dönüştürür. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | integer'a dönüştürür. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | float'a dönüştürür. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | float'a dönüştürür. |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring)() | String'e, ToString() yöntemi geçersiz kılınarak dönüştürür |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | String'e belirtilen formatla dönüştürür |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | String'e belirtilen formatla dönüştürür |

### Ayrıca Bakınız

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
