---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Görüntü Meta Verisi imza özelliklerini içerir."
type: docs
weight: 740
url: /tr/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Görüntü Meta Verisi imza özelliklerini içerir.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Id ve değer ile Image Metadata Signature oluşturur |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | İmza oluşturma tarihini al veya ayarla. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | İmza Değer özelliklerini kodlamak ve çözmek için [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Bu imzanın belgelerden silinip silinmediğini gösteren bayrağı al. Bu özellik yalnızca silinen imzaların listesini tutmak için belge geçmişi günlük kayıtlarında kullanılır. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Standart Image Metadata signature açıklamasını almak için yalnızca okunabilir değer |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | İmzanın yüksekliğini belirtir. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Image Metadata imzasının tanımlayıcısı. Önceden tanımlı Id değerine sahip standart Signature içeren ImageMetadataSignatures sınıfına bakın. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu gösteren bayrağı al veya ayarla. Bu özellik, öğeyi imza (true) ya da belge öğesi (false) olarak ayarlamak için Update yöntemiyle kullanılır. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | İmzanın sol konumunu belirtir. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | İmza değiştirme tarihini al veya ayarla. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Benzersiz meta veri adını belirtir. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | İmzanın bulunduğu sayfayı belirtir. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Güncelleme veya Silme yöntemleriyle belgede imzayı değiştirmek için benzersiz imza tanımlayıcısı. Bu özellik, Sign veya Search yöntemi çağrıldıktan sonra otomatik olarak ayarlanır. Bu özellik daha önce kaydedildiyse, imzayı manipüle etmek için manuel olarak ayarlanabilir. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | İmzanın türünü belirtir. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Metadata değerinin boyutunu almak için yalnızca okunabilir değer |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | İmzanın üst konumunu belirtir. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Meta veri değer tipini belirtir. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Meta veri nesnesini belirtir. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | İmzanın genişliğini belirtir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Meta Veri İmzası örneğini kopyalar. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Verilen değerle Image Metadata Signature örneğini klonla. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Serileştirme sonrası Meta Veri İmza Değerinden nesne elde eder. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Serileştirme sonrası Meta Veri İmza Metninden nesne elde eder. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | GetHashCode metodunu geçersiz kılar |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Boolean değere dönüştürür |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | DateTime'a dönüştürür. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | DateTime'a dönüştürür. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Decimal'a dönüştürür. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Decimal'a dönüştürür. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Double'a dönüştürür. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Double'a dönüştürür. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | integer'a dönüştürür. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Uzun (long) tipine dönüştürür. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | float'a dönüştürür. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | float'a dönüştürür. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | String'e, ToString() yöntemi geçersiz kılınarak dönüştürür |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | String'e belirtilen formatla dönüştürür |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | String'e belirtilen formatla dönüştürür |

### Ayrıca Bakınız

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
