---
title: ImageMetadataSignature
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Görüntü Meta Verileri imza özelliklerini içerir.
type: docs
weight: 570
url: /tr/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Görüntü Meta Verileri imza özelliklerini içerir.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | , Id ve value ile Görüntü Meta Veri İmzası Oluşturur |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | İmza oluşturma tarihini alın veya ayarlayın. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Şunun uygulanmasını alır veya ayarlar:[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) imza Değeri özelliklerini kodlamak ve kodunu çözmek için arayüz. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Bu imzanın belgeden silinip silinmediğini gösteren bayrağı alın. Bu özellik, silinen imzaların listesini tutmak için yalnızca belge geçmişi günlük kayıtları için kullanılır. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Standart Görüntü Meta Verisi imzası için açıklama almak üzere salt okunur değer |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | İmzanın yüksekliğini belirtir. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Görüntü Meta Verisi imzasının tanımlayıcısı. Bkz.ImageMetadataSignatures önceden tanımlanmış Kimlik değerine sahip standart İmza içeren sınıf. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu belirtmek için işaret alın veya ayarlayın. Bu özellik, öğeyi imza (doğru) veya belge öğesi (yanlış) olarak ayarlamak için Update yöntemiyle birlikte kullanılıyor. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | İmzanın sol konumunu belirtir. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | İmza değiştirme tarihini alın veya ayarlayın. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Benzersiz meta veri adını belirtir. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | . üzerinde bulunan sayfa imzasını belirtir |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Belgedeki imzayı Güncelleme veya Silme yöntemleri üzerinden değiştirmek için benzersiz imza tanımlayıcı. Bu özellik, İmzalama veya Arama yöntemi çağrıldıktan sonra otomatik olarak ayarlanacaktır. Bu özellik, imzayı değiştirmek için manuel olarak ayarlanmadan önce kaydedilmişse. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | İmza türünü belirtir. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Meta veri boyutunu almak için salt okunur değer value |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | İmzanın en üst konumunu belirtir. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Meta veri değeri türünü belirtir. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Meta veri nesnesini belirtir. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | İmza genişliğini belirtir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Klon Meta Veri İmza örneği. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Görüntü Meta Veri İmza örneğini verilen değerle Klonla. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | İmza özelliklerini karşılaştırmak için Equals yönteminin üzerine yazar |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Seri kaldırma üzerinden Meta Veri İmza Değerinden nesne elde edin. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Seri kaldırma üzerinden Meta Veri İmza Metninden nesne elde edin. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | GetHashCode yöntemini geçersiz kılar |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Boole değerine dönüştürür. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | DateTime. biçimine dönüştürür |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | DateTime. biçimine dönüştürür |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Ondalık Sayıya Dönüştürür. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Ondalık Sayıya Dönüştürür. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Çifte Dönüştürür. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Çifte Dönüştürür. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Tamsayıya dönüştürür. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Long'a dönüştürür. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Float'a dönüştürür. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Float'a dönüştürür. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | ToString() yöntemini geçersiz kılarak Dizeye dönüştürür |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Belirtilen format ile Dizeye dönüştürür |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Belirtilen format ile Dizeye dönüştürür |

### Ayrıca bakınız

* class [MetadataSignature](../metadatasignature)
* ad alanı [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
