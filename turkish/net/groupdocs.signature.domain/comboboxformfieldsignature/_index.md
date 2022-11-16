---
title: ComboboxFormFieldSignature
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Açılan kutu giriş formu alanı imza özelliklerini içerir.
type: docs
weight: 90
url: /tr/net/groupdocs.signature.domain/comboboxformfieldsignature/
---
## ComboboxFormFieldSignature class

Açılan kutu giriş formu alanı imza özelliklerini içerir.

```csharp
public sealed class ComboboxFormFieldSignature : FormFieldSignature
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ComboboxFormFieldSignature](comboboxformfieldsignature#constructor)(string) | Önceden tanımlanmış adla ComboboxFormFieldSignature oluşturur. |
| [ComboboxFormFieldSignature](comboboxformfieldsignature#constructor_1)(string, List&lt;string&gt;) | Önceden tanımlanmış ad ve seçenekler listesiyle ComboboxFormFieldSignature oluşturur. |
| [ComboboxFormFieldSignature](comboboxformfieldsignature#constructor_2)(string, List&lt;string&gt;, object) | Önceden tanımlanmış ad, seçenekler listesi ve seçilen değerle ComboboxFormFieldSignature oluşturur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | İmza oluşturma tarihini alın veya ayarlayın. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Bu imzanın belgeden silinip silinmediğini gösteren bayrağı alın. Bu özellik, silinen imzaların listesini tutmak için yalnızca belge geçmişi günlük kayıtları için kullanılır. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | İmzanın yüksekliğini belirtir. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu belirtmek için işaret alın veya ayarlayın. Bu özellik, öğeyi imza (doğru) veya belge öğesi (yanlış) olarak ayarlamak için Update yöntemiyle birlikte kullanılıyor. |
| [Items](../../groupdocs.signature.domain/comboboxformfieldsignature/items) { get; set; } | Açılan kutu seçenekleri listesini alın veya ayarlayın. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | İmzanın sol konumunu belirtir. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | İmza değiştirme tarihini alın veya ayarlayın. |
| [Name](../../groupdocs.signature.domain/formfieldsignature/name) { get; set; } | Benzersiz form alanı adını belirtir. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | . üzerinde bulunan sayfa imzasını belirtir |
| [Selected](../../groupdocs.signature.domain/comboboxformfieldsignature/selected) { get; set; } | Seçilen değeri alın veya ayarlayın. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Belgedeki imzayı Güncelleme veya Silme yöntemleri üzerinden değiştirmek için benzersiz imza tanımlayıcı. Bu özellik, İmzalama veya Arama yöntemi çağrıldıktan sonra otomatik olarak ayarlanacaktır. Bu özellik, imzayı değiştirmek için manuel olarak ayarlanmadan önce kaydedilmişse. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | İmza türünü belirtir. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | İmzanın en üst konumunu belirtir. |
| [Type](../../groupdocs.signature.domain/formfieldsignature/type) { get; } | Form alanı türünü belirtir. |
| [Value](../../groupdocs.signature.domain/formfieldsignature/value) { get; set; } | Form alanı veri nesnesini belirtir. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | İmza genişliğini belirtir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/comboboxformfieldsignature/clone)() | FormField Signature örneğini klonlayın. |
| override [Equals](../../groupdocs.signature.domain/comboboxformfieldsignature/equals)(object) | İmza özelliklerini karşılaştırmak için Equals yönteminin üzerine yazar |
| override [GetHashCode](../../groupdocs.signature.domain/comboboxformfieldsignature/gethashcode)() | GetHashCode yöntemini geçersiz kılar |

### Ayrıca bakınız

* class [FormFieldSignature](../formfieldsignature)
* ad alanı [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->