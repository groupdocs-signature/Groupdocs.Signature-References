---
title: "Sign"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يوقّع المستند باستخدام SignOptionsgroupdocs.signature.options/signoptions ويحفظ النتيجة إلى تدفق."
type: docs
weight: 160
url: /ar/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

يوقّع المستند باستخدام [`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى تدفق.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | دفق | تدفق المستند الناتج. |
| signOptions | SignOptions | خيارات التوقيع. |

### قيمة الإرجاع

إرجاع نسخة من [`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة بالتوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### انظر أيضًا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

يوقّع المستند باستخدام [`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى تدفق مع [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) المحددة مسبقًا.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | دفق | تدفق المستند الناتج. |
| signOptions | SignOptions | خيارات التوقيع. |
| saveOptions | خيارات الحفظ | خيارات الحفظ. |

### قيمة الإرجاع

إرجاع نسخة من [`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة بالتوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### انظر أيضًا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

يوقّع المستند باستخدام مجموعة من [`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى تدفق.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | دفق | تدفق المستند الناتج. |
| signOptionsList | List`1 | قائمة خيارات التوقيع. |

### قيمة الإرجاع

إرجاع نسخة من [`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة بالتوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### انظر أيضًا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

يوقع المستند بمجموعة من [`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى تدفق مع [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) المحددة مسبقًا.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | دفق | تدفق المستند الناتج. |
| signOptionsList | List`1 | قائمة خيارات التوقيع. |
| saveOptions | خيارات الحفظ | خيارات الحفظ. |

### قيمة الإرجاع

إرجاع نسخة من [`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة بالتوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### انظر أيضًا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

يوقع المستند باستخدام [`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار ملف الإخراج. |
| signOptions | SignOptions | خيارات التوقيع. |

### قيمة الإرجاع

إرجاع نسخة من [`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة بالتوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### انظر أيضًا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

يوقع المستند باستخدام [`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد مع [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) المحددة مسبقًا.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار ملف الإخراج. |
| signOptions | SignOptions | خيارات التوقيع. |
| saveOptions | خيارات الحفظ | خيارات الحفظ. |

### قيمة الإرجاع

إرجاع نسخة من [`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة بالتوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### انظر أيضًا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

يوقع المستند بمجموعة من [`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار ملف الإخراج. |
| signOptionsList | List`1 | قائمة خيارات التوقيع. |

### قيمة الإرجاع

إرجاع نسخة من [`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة بالتوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### انظر أيضًا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

يوقع المستند بمجموعة من [`SignOptions`](../../../groupdocs.signature.options/signoptions) ويحفظ النتيجة إلى مسار الملف المحدد مع [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) المحددة مسبقًا.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار ملف الإخراج. |
| signOptionsList | List`1 | قائمة خيارات التوقيع. |
| saveOptions | خيارات الحفظ | خيارات الحفظ. |

### قيمة الإرجاع

إرجاع نسخة من [`SignResult`](../../../groupdocs.signature.domain/signresult) مع قائمة بالتوقيعات التي تم إنشاؤها حديثًا.

### ملاحظات

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### انظر أيضًا

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
