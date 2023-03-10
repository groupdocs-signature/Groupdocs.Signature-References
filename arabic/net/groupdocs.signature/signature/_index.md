---
title: Signature
second_title: GroupDocs.Signature لمرجع .NET API
description: يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند.
type: docs
weight: 1880
url: /ar/net/groupdocs.signature/signature/
---
## Signature class

يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند.

```csharp
public class Signature : IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Signature](signature#constructor)(Stream) | تهيئة مثيل جديد لـ[`Signature`](../signature) فئة مع المستند المقدم من تيار. |
| [Signature](signature#constructor_4)(string) | تهيئة مثيل جديد لـ[`Signature`](../signature) مثيل فئة مع المستند المقدم بواسطة مسار الملف. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | تهيئة مثيل جديد لـ[`Signature`](../signature) فئة مع المستند المقدم من خلال خيارات الدفق والتحميلLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | تهيئة مثيل جديد لـ[`Signature`](../signature)مثيل فئة مع المستند المقدم بواسطة تيار و[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | تهيئة مثيل جديد لـ[`Signature`](../signature) مثيل فئة مع المستند المقدم بواسطة مسار الملف وLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | تهيئة مثيل جديد لـ[`Signature`](../signature) مثيل فئة مع المستند المقدم بواسطة مسار الملف و[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | تهيئة مثيل جديد لـ[`Signature`](../signature) مثيل فئة مع المستند المقدم من خيارات الدفق والتحميلLoadOptions والإعدادات[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | تهيئة مثيل جديد لـ[`Signature`](../signature) مثيل فئة مع المستند المقدم بواسطة مسار الملف ،LoadOptions و[`SignatureSettings`](../signaturesettings) . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | حذف التوقيع الذي تم تمريره[`BaseSignature`](../../groupdocs.signature.domain/basesignature) من الوثيقة. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | حذف قائمة التوقيعات التي تم تمريرها[`BaseSignature`](../../groupdocs.signature.domain/basesignature) من الوثيقة. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | حذف تواقيع قائمة الأنواع المعينة[`SignatureType`](../../groupdocs.signature.domain/signaturetype) من المستند . التوقيعات التي تمت إضافتها بواسطة طريقة التوقيع فقط وتم تمييزها على أنها تواقيع[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) أنواع التوقيعات التالية مدعومة: نص ، صورة ، رقمي ، باركود ، QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | حذف قائمة التوقيعات التي تم تمريرها[`BaseSignature`](../../groupdocs.signature.domain/basesignature) من الوثيقة. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | حذف التوقيعات من نوع معين[`SignatureType`](../../groupdocs.signature.domain/signaturetype) من المستند . التوقيعات التي تمت إضافتها بواسطة طريقة التوقيع فقط وتم تمييزها على أنها تواقيع[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) أنواع التوقيعات التالية مدعومة: نص ، صورة ، رقمي ، باركود ، QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | حذف التوقيع بمعرف التوقيع المحدد الخاص به من المستند. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | تنفيذ واجهة IDisposable لتنظيف الموارد الداخلية |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | يولد معاينة لصفحات المستند . |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | الحصول على معلومات حول صفحات المستند: أحجامها ، أقصى ارتفاع للصفحة ، عرض الصفحة بأقصى ارتفاع . |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | يبحث عن التوقيعات في مستند بواسطة[`SearchOptions`](../../groupdocs.signature.options/searchoptions) القائمة . |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | يبحث عن أنواع التوقيع المحددة في المستند بواسطة[`SignatureType`](../../groupdocs.signature.domain/signaturetype) القيمة . |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | يبحث عن التوقيعات في مستند بواسطة[`SearchOptions`](../../groupdocs.signature.options/searchoptions) خيارات. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | يبحث عن نوع التوقيع الدقيق في المستند بواسطة[`SignatureType`](../../groupdocs.signature.domain/signaturetype) القيمة . |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | توقيع وثيقة مع مجموعة من[`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في تيار . |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | توقيع الوثيقة مع[`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في تيار . |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | توقيع وثيقة مع مجموعة من[`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في مسار الملف المحدد. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | توقيع الوثيقة مع[`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في مسار الملف المحدد. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | توقيع وثيقة مع مجموعة من[`SignOptions`](../../groupdocs.signature.options/signoptions)ويحفظ النتيجة في دفق محدد مسبقًا[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | توقيع الوثيقة مع[`SignOptions`](../../groupdocs.signature.options/signoptions)ويحفظ النتيجة في دفق محدد مسبقًا[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | توقيع وثيقة مع مجموعة من[`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد مع محدد مسبقًا[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | توقيع الوثيقة مع[`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد مع محدد مسبقًا[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | اجتازت التحديثات التوقيع[`BaseSignature`](../../groupdocs.signature.domain/basesignature) في المستند. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | اجتازت التحديثات التوقيعات[`BaseSignature`](../../groupdocs.signature.domain/basesignature) في المستند. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | التحقق من توقيعات المستند بقائمة بيانات VerifyOptions . |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | التحقق من توقيعات المستند ببيانات VerifyOptions المقدمة . |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | يولد معاينة التوقيع بناءً على خيارات SignOptions المحددة.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## الأحداث

| اسم | وصف |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | يحدث عند اكتمال عملية البحث عن التوقيع. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | يحدث عندما يتغير تقدم عملية البحث عن التوقيع. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | يحدث عند بدء عملية البحث عن التوقيع. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | يحدث عند اكتمال عملية توقيع المستند. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | يحدث عند تغيير تقدم عملية توقيع المستند. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | يحدث عند بدء عملية توقيع المستند. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | يحدث عند اكتمال عملية التحقق من التوقيع. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | يحدث عندما يتغير تقدم عملية التحقق من التوقيع. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | يحدث عند بدء عملية التحقق من التوقيع. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول GroupDocs. ميزات التوقيع: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### أنظر أيضا

* مساحة الاسم [GroupDocs.Signature](../../groupdocs.signature)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
