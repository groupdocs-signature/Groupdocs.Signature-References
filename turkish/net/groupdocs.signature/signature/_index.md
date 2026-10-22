---
title: "İmza"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Belge imzalama sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 2170
url: /tr/net/groupdocs.signature/signature/
---
## Signature class

Belge imzalama sürecini kontrol eden ana sınıfı temsil eder.

```csharp
public class Signature : IDisposable
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Akış tarafından sağlanan belge ile yeni bir [`Signature`](../signature) sınıf örneği başlatır. |
| [Signature](signature#constructor_4)(string) | Dosya yolu ile sağlanan belge ile yeni bir [`Signature`](../signature) sınıf örneği başlatır. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Akış tarafından sağlanan belge ve yükleme seçenekleri LoadOptions ile yeni bir [`Signature`](../signature) sınıf örneği başlatır. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Akış tarafından sağlanan belge ve [`SignatureSettings`](../signaturesettings) ile yeni bir [`Signature`](../signature) sınıf örneği başlatır. |
| [Signature](signature#constructor_5)(string, LoadOptions) | Dosya yolu ile sağlanan belge ve LoadOptions ile yeni bir [`Signature`](../signature) sınıf örneği başlatır. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Dosya yolu ile sağlanan belge ve [`SignatureSettings`](../signaturesettings) ile yeni bir [`Signature`](../signature) sınıf örneği başlatır. |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Akış tarafından sağlanan belge, yükleme seçenekleri LoadOptions ve ayarlar [`SignatureSettings`](../signaturesettings) ile yeni bir [`Signature`](../signature) sınıf örneği başlatır. |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Dosya yolu ile sağlanan belge, LoadOptions ve [`SignatureSettings`](../signaturesettings) ile yeni bir [`Signature`](../signature) sınıf örneği başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Belgeden verilen imza [`BaseSignature`](../../groupdocs.signature.domain/basesignature) siler. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Belgeden verilen imza listesi [`BaseSignature`](../../groupdocs.signature.domain/basesignature) siler. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Belgeden belirli tipteki imzalar listesi [`SignatureType`](../../groupdocs.signature.domain/signaturetype) siler. Yalnızca Sign yöntemiyle eklenen ve Imza [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) olarak işaretlenen imzalar kaldırılacaktır. Desteklenen imza tipleri şunlardır: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Belgeden verilen imza listesi [`BaseSignature`](../../groupdocs.signature.domain/basesignature) siler. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Belgeden belirli bir tipteki imzalar [`SignatureType`](../../groupdocs.signature.domain/signaturetype) siler. Yalnızca Sign yöntemiyle eklenen ve Imza [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) olarak işaretlenen imzalar kaldırılacaktır. Desteklenen imza tipleri şunlardır: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Belgeden belirli imza Id'siyle imzayı siler. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | İç kaynakları temizlemek için IDisposable arayüzünü uygular. |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Belge sayfalarının önizlemesini oluşturur. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip sayfanın genişliği. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Belgedeki imzaları mevcut tüm arama seçeneklerini kullanarak arar ve belirtilen koşula göre sonuçları filtreler. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Bir belgede imzaları, [`SearchOptions`](../../groupdocs.signature.options/searchoptions) listesiyle arar. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Belgedeki belirtilen imza türlerini, [`SignatureType`](../../groupdocs.signature.domain/signaturetype) değeriyle arar. |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Belgedeki imzaları, sağlanan arama seçeneklerini kullanarak arar ve sonuçları belirtilen koşula göre filtreler. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Bir belgede imzaları, [`SearchOptions`](../../groupdocs.signature.options/searchoptions) seçenekleriyle arar. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Belgedeki imzaların kesin türünü, [`SignatureType`](../../groupdocs.signature.domain/signaturetype) değeriyle arar. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Belgeyi, [`SignOptions`](../../groupdocs.signature.options/signoptions) koleksiyonuyla imzalar ve sonucu bir akışa kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Belgeyi, [`SignOptions`](../../groupdocs.signature.options/signoptions) ile imzalar ve sonucu bir akışa kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Belgeyi, [`SignOptions`](../../groupdocs.signature.options/signoptions) koleksiyonuyla imzalar ve sonucu belirtilen dosya yoluna kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Belgeyi, [`SignOptions`](../../groupdocs.signature.options/signoptions) ile imzalar ve sonucu belirtilen dosya yoluna kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Belgeyi, [`SignOptions`](../../groupdocs.signature.options/signoptions) koleksiyonuyla imzalar ve sonucu önceden tanımlı [`SaveOptions`](../../groupdocs.signature.options/saveoptions) ile bir akışa kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Belgeyi, [`SignOptions`](../../groupdocs.signature.options/signoptions) ile imzalar ve sonucu önceden tanımlı [`SaveOptions`](../../groupdocs.signature.options/saveoptions) ile bir akışa kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Belgeyi, [`SignOptions`](../../groupdocs.signature.options/signoptions) koleksiyonuyla imzalar ve sonucu önceden tanımlı [`SaveOptions`](../../groupdocs.signature.options/saveoptions) ile belirtilen dosya yoluna kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Belgeyi, [`SignOptions`](../../groupdocs.signature.options/signoptions) ile imzalar ve sonucu önceden tanımlı [`SaveOptions`](../../groupdocs.signature.options/saveoptions) ile belirtilen dosya yoluna kaydeder. |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Belgedeki verilen imzayı [`BaseSignature`](../../groupdocs.signature.domain/basesignature) günceller. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Belgedeki verilen imzaları [`BaseSignature`](../../groupdocs.signature.domain/basesignature) günceller. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Belge imzalarını VerifyOptions verileri listesiyle doğrular. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Belge imzalarını verilen VerifyOptions verileriyle doğrular. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Belge imzalarını mevcut tüm doğrulama seçeneklerini kullanarak doğrular ve sonuçları belirtilen koşula göre filtreler. Bu yöntem önce doğrulama seçenekleriyle eşleşen imzaları arar, bunları koşula göre filtreler ve ardından yalnızca filtrelenen imzaları doğrular. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Belge imzalarını sağlanan doğrulama seçeneklerini kullanarak doğrular ve sonuçları belirtilen koşula göre filtreler. Bu yöntem önce doğrulama seçenekleriyle eşleşen imzaları arar, bunları koşula göre filtreler ve ardından yalnızca filtrelenen imzaları doğrular. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Verilen SignOptions temelinde İmza önizlemesi oluşturur. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Olaylar

| Ad | Açıklama |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | İmza arama işlemi tamamlandığında gerçekleşir. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | İmza arama işlemi ilerlemesi değiştiğinde gerçekleşir. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | İmza arama işlemi başlatıldığında gerçekleşir. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Belge imzalama işlemi tamamlandığında gerçekleşir. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Belge imzalama süreci ilerlemesi değiştiğinde oluşur. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Belge imzalama süreci başladığında oluşur. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | İmza doğrulama süreci tamamlandığında oluşur. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | İmza doğrulama süreci ilerlemesi değiştiğinde oluşur. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | İmza doğrulama süreci başladığında oluşur. |

### Açıklamalar

**Learn more**

GroupDocs.Signature özellikleri hakkında daha fazla bilgi: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Ayrıca Bakınız

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
