---
title: "توقيع"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند."
type: docs
weight: 2170
url: /ar/net/groupdocs.signature/signature/
---
## Signature class

يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند.

```csharp
public class Signature : IDisposable
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Signature](signature#constructor)(Stream) | ينشئ نسخة جديدة من الفئة [`Signature`](../signature) مع مستند موفر عبر الدفق. |
| [Signature](signature#constructor_4)(string) | ينشئ نسخة جديدة من الفئة [`Signature`](../signature) مع مستند موفر عبر مسار الملف. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | ينشئ نسخة جديدة من الفئة [`Signature`](../signature) مع مستند موفر عبر الدفق وخيارات التحميل LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | ينشئ نسخة جديدة من الفئة [`Signature`](../signature) مع مستند موفر عبر الدفق و[`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | ينشئ نسخة جديدة من الفئة [`Signature`](../signature) مع مستند موفر عبر مسار الملف وLoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | ينشئ نسخة جديدة من الفئة [`Signature`](../signature) مع مستند موفر عبر مسار الملف و[`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | ينشئ نسخة جديدة من الفئة [`Signature`](../signature) مع مستند موفر عبر الدفق، وخيارات التحميل LoadOptions والإعدادات [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | ينشئ نسخة جديدة من الفئة [`Signature`](../signature) مع مستند موفر عبر مسار الملف، LoadOptions و[`SignatureSettings`](../signaturesettings). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | يحذف التوقيع الممرر [`BaseSignature`](../../groupdocs.signature.domain/basesignature) من المستند. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | يحذف القائمة الممررة من التوقيعات [`BaseSignature`](../../groupdocs.signature.domain/basesignature) من المستند. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | يحذف التوقيعات من قائمة أنواع معينة [`SignatureType`](../../groupdocs.signature.domain/signaturetype) من المستند. فقط التوقيعات التي أضيفت بواسطة أسلوب Sign وتم وضع علامة عليها كـ توقيعات [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) سيتم إزالتها. الأنواع التالية من التوقيعات مدعومة: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | يحذف القائمة الممررة من التوقيعات [`BaseSignature`](../../groupdocs.signature.domain/basesignature) من المستند. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | يحذف التوقيعات من نوع معين [`SignatureType`](../../groupdocs.signature.domain/signaturetype) من المستند. فقط التوقيعات التي أضيفت بواسطة أسلوب Sign وتم وضع علامة عليها كـ توقيعات [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) سيتم إزالتها. الأنواع التالية من التوقيعات مدعومة: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | يحذف التوقيع بواسطة معرف توقيعه المحدد من المستند. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | تنفيذ واجهة IDisposable لتنظيف الموارد الداخلية |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | ينشئ معاينة لصفحات المستند. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، عرض الصفحة ذات أقصى ارتفاع. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | يبحث عن التوقيعات في المستند باستخدام جميع خيارات البحث المتاحة ويصفي النتائج بناءً على الشرط المحدد. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | يبحث عن التوقيعات في مستند باستخدام قائمة [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | يبحث عن أنواع التوقيع المحددة في المستند باستخدام قيمة [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | يبحث عن التوقيعات في المستند باستخدام خيارات البحث المقدمة ويصفي النتائج بناءً على الشرط المحدد. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | يبحث عن التوقيعات في مستند باستخدام خيارات [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | يبحث عن النوع الدقيق للتوقيعات في المستند باستخدام قيمة [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | يوقع المستند باستخدام مجموعة من [`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى تدفق. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | يوقع المستند باستخدام [`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى تدفق. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | يوقع المستند باستخدام مجموعة من [`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | يوقع المستند باستخدام [`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | يوقع المستند باستخدام مجموعة من [`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى تدفق مع [`SaveOptions`](../../groupdocs.signature.options/saveoptions) معرفة مسبقًا. |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | يوقع المستند باستخدام [`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى تدفق مع [`SaveOptions`](../../groupdocs.signature.options/saveoptions) معرفة مسبقًا. |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | يوقع المستند باستخدام مجموعة من [`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد مع [`SaveOptions`](../../groupdocs.signature.options/saveoptions) معرفة مسبقًا. |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | يوقع المستند باستخدام [`SignOptions`](../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد مع [`SaveOptions`](../../groupdocs.signature.options/saveoptions) معرفة مسبقًا. |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | يقوم بتحديث التوقيع [`BaseSignature`](../../groupdocs.signature.domain/basesignature) الممرَّر في المستند. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | يقوم بتحديث التوقيعات [`BaseSignature`](../../groupdocs.signature.domain/basesignature) الممرَّرة في المستند. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | يتحقق من توقيعات المستند باستخدام قائمة بيانات VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | يتحقق من توقيعات المستند باستخدام جميع خيارات التحقق المتاحة ويصفي النتائج بناءً على الشرط المحدد. تقوم هذه الطريقة أولاً بالبحث عن التوقيعات التي تطابق خيارات التحقق، ثم تصفيتها باستخدام الشرط، وأخيرًا تتحقق فقط من التوقيعات التي تم تصفيتها. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | يتحقق من توقيعات المستند باستخدام خيارات التحقق المقدمة ويصفي النتائج بناءً على الشرط المحدد. تقوم هذه الطريقة أولاً بالبحث عن التوقيعات التي تطابق خيارات التحقق، ثم تصفيتها باستخدام الشرط، وأخيرًا تتحقق فقط من التوقيعات التي تم تصفيتها. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | ينشئ معاينة للتوقيع بناءً على SignOptions المعطاة. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | يحدث عندما تكتمل عملية البحث عن التوقيع. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | يحدث عندما يتغير تقدم عملية البحث عن التوقيع. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | يحدث عندما تبدأ عملية البحث عن التوقيع. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | يحدث عندما تكتمل عملية توقيع المستند. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | يحدث عندما يتغيّر تقدم عملية توقيع المستند. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | يحدث عندما تبدأ عملية توقيع المستند. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | يحدث عندما تكتمل عملية التحقق من التوقيع. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | يحدث عندما يتغيّر تقدم عملية التحقق من التوقيع. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | يحدث عندما تبدأ عملية التحقق من التوقيع. |

### ملاحظات

**Learn more**

مزيد من المعلومات حول ميزات GroupDocs.Signature: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### انظر أيضًا

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
