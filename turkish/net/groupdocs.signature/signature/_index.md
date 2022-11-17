---
title: Signature
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Belge imzalama sürecini kontrol eden ana sınıfı temsil eder.
type: docs
weight: 1800
url: /tr/net/groupdocs.signature/signature/
---
## Signature class

Belge imzalama sürecini kontrol eden ana sınıfı temsil eder.

```csharp
public class Signature : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Yeni örneğini başlatır[`Signature`](../signature) stream. tarafından sağlanan belgeye sahip sınıf |
| [Signature](signature#constructor_4)(string) | Yeni örneğini başlatır[`Signature`](../signature) dosya yolu tarafından sağlanan belgeye sahip sınıf örneği. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Yeni örneğini başlatır[`Signature`](../signature) akış ve yükleme seçenekleri tarafından sağlanan belgeye sahip sınıfLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Yeni örneğini başlatır[`Signature`](../signature) akış tarafından sağlanan belgeyle sınıf örneği ve[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Yeni örneğini başlatır[`Signature`](../signature) dosya yolu tarafından sağlanan belge ile sınıf örneği veLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Yeni örneğini başlatır[`Signature`](../signature) dosya yolu tarafından sağlanan belge ile sınıf örneği ve[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Yeni örneğini başlatır[`Signature`](../signature) akış tarafından sağlanan belge ile sınıf örneği, yükleme seçenekleriLoadOptions ve ayarlar[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Yeni örneğini başlatır[`Signature`](../signature) dosya yolu tarafından sağlanan belge ile sınıf örneği,LoadOptions ve[`SignatureSettings`](../signaturesettings) . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Geçilen imzayı siler[`BaseSignature`](../../groupdocs.signature.domain/basesignature) belgeden. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Geçilen imza listesini siler[`BaseSignature`](../../groupdocs.signature.domain/basesignature) belgeden. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Belirli türler listesinin imzalarını siler[`SignatureType`](../../groupdocs.signature.domain/signaturetype) Document. Yalnızca Sign yöntemiyle eklenen ve İmza olarak işaretlenen imzalar[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) kaldırılacak. Aşağıdaki imza türleri desteklenir: Metin, Resim, Dijital, Barkod, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Geçilen imza listesini siler[`BaseSignature`](../../groupdocs.signature.domain/basesignature) belgeden. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Belirli türdeki imzaları siler[`SignatureType`](../../groupdocs.signature.domain/signaturetype) Document. Yalnızca Sign yöntemiyle eklenen ve İmza olarak işaretlenen imzalar[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) kaldırılacak. Aşağıdaki imza türleri desteklenir: Metin, Resim, Dijital, Barkod, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Belgeden özel imza kimliğine göre imzayı siler. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Dahili kaynakları temizlemek için IDisposable arabirimi uygulayın |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Belge sayfaları önizlemesi oluşturur. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip bir sayfanın genişliği. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Şuna göre bir belgede imza arar:[`SearchOptions`](../../groupdocs.signature.options/searchoptions) liste. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Şuna göre belgede belirtilen imza türlerini arar:[`SignatureType`](../../groupdocs.signature.domain/signaturetype) değer. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Şuna göre bir belgede imza arar:[`SearchOptions`](../../groupdocs.signature.options/searchoptions) seçenekler. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Şuna göre belgedeki tam imza türlerini arar:[`SignatureType`](../../groupdocs.signature.domain/signaturetype) değer. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Belgeyi şu koleksiyonla imzalar:[`SignOptions`](../../groupdocs.signature.options/signoptions) ve sonucu bir akışa kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Belgeyi şununla imzalar:[`SignOptions`](../../groupdocs.signature.options/signoptions) ve sonucu bir akışa kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Belgeyi şu koleksiyonla imzalar:[`SignOptions`](../../groupdocs.signature.options/signoptions) ve sonucu belirtilen dosya yoluna kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Belgeyi şununla imzalar:[`SignOptions`](../../groupdocs.signature.options/signoptions) ve sonucu belirtilen dosya yoluna kaydeder. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Belgeyi şu koleksiyonla imzalar:[`SignOptions`](../../groupdocs.signature.options/signoptions) ve sonucu önceden tanımlanmış bir akışa kaydeder[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Belgeyi şununla imzalar:[`SignOptions`](../../groupdocs.signature.options/signoptions) ve sonucu önceden tanımlanmış bir akışa kaydeder[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Belgeyi şu koleksiyonla imzalar:[`SignOptions`](../../groupdocs.signature.options/signoptions) ve sonucu önceden tanımlanmış dosya yoluna kaydeder[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Belgeyi şununla imzalar:[`SignOptions`](../../groupdocs.signature.options/signoptions) ve sonucu önceden tanımlanmış dosya yoluna kaydeder[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Güncellemeler imzayı geçti[`BaseSignature`](../../groupdocs.signature.domain/basesignature) belgede. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Güncellemeler imzaları geçti[`BaseSignature`](../../groupdocs.signature.domain/basesignature) belgede. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Belge imzalarını VerifyOptions verileri listesiyle doğrular. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verilen VerifyOptions verileriyle belge imzalarını doğrular. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Verilen SignOptions'a göre İmza önizlemesi oluşturur.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Olaylar

| İsim | Tanım |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | İmza arama işlemi tamamlandığında gerçekleşir. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | İmza arama işlemi ilerleme durumu değiştiğinde gerçekleşir. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | İmza arama işlemi başladığında gerçekleşir. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Belge imzalama işlemi tamamlandığında gerçekleşir. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Belge imzalama işlemi ilerleme durumu değiştiğinde gerçekleşir. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Belge imzalama işlemi başladığında gerçekleşir. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | İmza doğrulama işlemi tamamlandığında gerçekleşir. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | İmza doğrulama işlemi ilerleme durumu değiştiğinde gerçekleşir. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | İmza doğrulama işlemi başladığında gerçekleşir. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs hakkında daha fazla bilgi.İmza özellikleri: [GroupDocs.Signature Geliştirici Kılavuzu](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Ayrıca bakınız

* ad alanı [GroupDocs.Signature](../../groupdocs.signature)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
