---
title: "Verify"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة."
type: docs
weight: 180
url: /ar/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| verifyOptions | VerifyOptions | خيارات التحقق من التوقيع. |

### قيمة الإرجاع

إرجاع نسخة من [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). الخاصية VerificationResult.IsValid تُعيد true إذا كانت عملية التحقق ناجحة.

### ملاحظات

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### انظر أيضًا

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

يتحقق من توقيعات المستند باستخدام خيارات التحقق المقدمة ويصفي النتائج بناءً على الشرط المحدد. تقوم هذه الطريقة أولاً بالبحث عن التوقيعات التي تطابق خيارات التحقق، ثم تصفيتها باستخدام الشرط، وأخيرًا تتحقق فقط من التوقيعات التي تم تصفيتها.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| verifyOptions | VerifyOptions | خيارات التحقق من التوقيع. |
| predicate | Func`2 | دالة الترشيح لتحديد أي التوقيعات يجب التحقق منها. |

### قيمة الإرجاع

يعيد قائمة من كائنات [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) التي تلبي الشرط المحدد.

### ملاحظات

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### انظر أيضًا

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

يتحقق من توقيعات المستند باستخدام قائمة بيانات VerifyOptions.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| verifyOptionsList | List`1 | مجموعة خيارات التحقق من التوقيع. نسخة من VerifyOptionsCollection. |

### قيمة الإرجاع

إرجاع نسخة من [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). الخاصية VerificationResult.IsValid تُعيد true إذا كانت عملية التحقق ناجحة.

### ملاحظات

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### انظر أيضًا

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

يتحقق من توقيعات المستند باستخدام جميع خيارات التحقق المتاحة ويصفي النتائج بناءً على الشرط المحدد. تقوم هذه الطريقة أولاً بالبحث عن التوقيعات التي تطابق خيارات التحقق، ثم تصفيتها باستخدام الشرط، وأخيرًا تتحقق فقط من التوقيعات التي تم تصفيتها.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| verifyOptionsList | List`1 | مجموعة خيارات التحقق من التوقيع. نسخة من VerifyOptionsCollection. |
| predicate | Func`2 | دالة الترشيح لتحديد أي التوقيعات يجب التحقق منها. |

### قيمة الإرجاع

يعيد قائمة من كائنات [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) التي تلبي الشرط المحدد.

### ملاحظات

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### انظر أيضًا

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
