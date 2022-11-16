---
title: Sign
second_title: GroupDocs.Signature لمرجع .NET API
description: توقيع الوثيقة معSignOptionsgroupdocs.signature.options/signoptions ويحفظ النتيجة في تيار .
type: docs
weight: 160
url: /ar/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

توقيع الوثيقة مع[`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في تيار .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | تدفق وثيقة الإخراج. |
| signOptions | SignOptions | خيارات التوقيع. |

### قيمة الإرجاع

إرجاع مثيل[`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة التوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التوقيع الإلكتروني التي يدعمها GroupDocs. التوقيع: [أنواع التوقيعات الإلكترونية التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* المزيد حول كيفية استخدام مستندات eSign في C #: [كيفية التوقيع الإلكتروني للمستندات باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### أنظر أيضا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

توقيع الوثيقة مع[`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في دفق محدد مسبقًا[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | تدفق وثيقة الإخراج. |
| signOptions | SignOptions | خيارات التوقيع. |
| saveOptions | SaveOptions | خيارات الحفظ. |

### قيمة الإرجاع

إرجاع مثيل[`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة التوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التوقيع الإلكتروني التي يدعمها GroupDocs. التوقيع: [أنواع التوقيعات الإلكترونية التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* المزيد حول كيفية استخدام مستندات eSign في C #: [كيفية التوقيع الإلكتروني للمستندات باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* المزيد حول كيفية حفظ المستندات الموقعة إلكترونيًا وتخصيص عملية الحفظ: [كيفية تخصيص المستندات الموقعة إلكترونيًا عند الحفظ باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### أنظر أيضا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

توقيع وثيقة مع مجموعة من[`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في تيار .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | تدفق وثيقة الإخراج. |
| signOptionsList | List`1 | قائمة خيارات التوقيع. |

### قيمة الإرجاع

إرجاع مثيل[`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة التوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التوقيع الإلكتروني التي يدعمها GroupDocs. التوقيع: [أنواع التوقيعات الإلكترونية التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* المزيد حول كيفية استخدام مستندات eSign في C #: [كيفية التوقيع الإلكتروني للمستندات باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### أنظر أيضا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

توقيع وثيقة مع مجموعة من[`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في دفق محدد مسبقًا[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | تدفق وثيقة الإخراج. |
| signOptionsList | List`1 | قائمة خيارات التوقيع. |
| saveOptions | SaveOptions | خيارات الحفظ. |

### قيمة الإرجاع

إرجاع مثيل[`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة التوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التوقيع الإلكتروني التي يدعمها GroupDocs. التوقيع: [أنواع التوقيعات الإلكترونية التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* المزيد حول كيفية استخدام مستندات eSign في C #: [كيفية التوقيع الإلكتروني للمستندات باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* المزيد حول كيفية حفظ المستندات الموقعة إلكترونيًا وتخصيص عملية الحفظ: [كيفية تخصيص المستندات الموقعة إلكترونيًا عند الحفظ باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### أنظر أيضا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

توقيع الوثيقة مع[`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في مسار الملف المحدد.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار ملف الإخراج. |
| signOptions | SignOptions | خيارات التوقيع. |

### قيمة الإرجاع

إرجاع مثيل[`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة التوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التوقيع الإلكتروني التي يدعمها GroupDocs. التوقيع: [أنواع التوقيعات الإلكترونية التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* المزيد حول كيفية استخدام مستندات eSign في C #: [كيفية التوقيع الإلكتروني للمستندات باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### أنظر أيضا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

توقيع الوثيقة مع[`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد مع محدد مسبقًا[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار ملف الإخراج. |
| signOptions | SignOptions | خيارات التوقيع. |
| saveOptions | SaveOptions | خيارات الحفظ. |

### قيمة الإرجاع

إرجاع مثيل[`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة التوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التوقيع الإلكتروني التي يدعمها GroupDocs. التوقيع: [أنواع التوقيعات الإلكترونية التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* المزيد حول كيفية استخدام مستندات eSign في C #: [كيفية التوقيع الإلكتروني للمستندات باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* المزيد حول كيفية حفظ المستندات الموقعة إلكترونيًا وتخصيص عملية الحفظ: [كيفية تخصيص المستندات الموقعة إلكترونيًا عند الحفظ باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### أنظر أيضا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

توقيع وثيقة مع مجموعة من[`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة في مسار الملف المحدد.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار ملف الإخراج. |
| signOptionsList | List`1 | قائمة خيارات التوقيع. |

### قيمة الإرجاع

إرجاع مثيل[`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة التوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التوقيع الإلكتروني التي يدعمها GroupDocs. التوقيع: [أنواع التوقيعات الإلكترونية التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* المزيد حول كيفية استخدام مستندات eSign في C #: [كيفية التوقيع الإلكتروني للمستندات باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### أنظر أيضا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

توقيع وثيقة مع مجموعة من[`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد مع محدد مسبقًا[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار ملف الإخراج. |
| signOptionsList | List`1 | قائمة خيارات التوقيع. |
| saveOptions | SaveOptions | خيارات الحفظ. |

### قيمة الإرجاع

إرجاع مثيل[`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة التوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع التوقيع الإلكتروني التي يدعمها GroupDocs. التوقيع: [أنواع التوقيعات الإلكترونية التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* المزيد حول كيفية استخدام مستندات eSign في C #: [كيفية التوقيع الإلكتروني للمستندات باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* المزيد حول كيفية حفظ المستندات الموقعة إلكترونيًا وتخصيص عملية الحفظ: [كيفية تخصيص المستندات الموقعة إلكترونيًا عند الحفظ باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### أنظر أيضا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
