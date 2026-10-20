---
title: "بحث"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يبحث عن التوقيعات في مستند باستخدام قائمة SearchOptionsgroupdocs.signature.options/searchoptions."
type: docs
weight: 150
url: /ar/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

يبحث عن التوقيعات في مستند باستخدام قائمة [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| searchOptionsList | List`1 | مجموعة خيارات البحث. |

### قيمة الإرجاع

يعيد مثيلاً من [`SearchResult`](../../../groupdocs.signature.domain/searchresult) مع قائمة التوقيعات التي تم العثور عليها.

### ملاحظات

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### انظر أيضًا

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

يبحث عن التوقيعات في المستند باستخدام خيارات البحث المقدمة ويصفي النتائج بناءً على الشرط المحدد.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| searchOptionsList | List`1 | قائمة من مثيلات [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) التي تحدد معايير البحث عن التوقيعات. |
| predicate | Func`2 | دالة الترشيح لتطبيقها على قائمة التوقيعات التي تم العثور عليها. |

### قيمة الإرجاع

يعيد [`SearchResult`](../../../groupdocs.signature.domain/searchresult) يحتوي على التوقيعات التي تطابق خيارات البحث المحددة وتستوفي دالة الترشيح.

### ملاحظات

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### انظر أيضًا

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

يبحث عن التوقيعات في مستند باستخدام خيارات [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| searchOptions | SearchOptions | خيارات البحث. |

### قيمة الإرجاع

يعيد قائمة التوقيعات التي تم العثور عليها.

### ملاحظات

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### انظر أيضًا

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

يبحث عن النوع الدقيق للتوقيعات في المستند باستخدام قيمة [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureType | SignatureType | نوع التوقيعات للبحث. |

### قيمة الإرجاع

يعيد قائمة التوقيعات التي تم العثور عليها بالنوع الدقيق.

### ملاحظات

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### انظر أيضًا

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

يبحث عن أنواع التوقيعات المحددة في المستند باستخدام قيمة [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureTypes | SignatureType[] | نوع أو عدة أنواع من التوقيعات للعثور عليها. |

### قيمة الإرجاع

يعيد كائنًا من [`SearchResult`](../../../groupdocs.signature.domain/searchresult) مع قائمة بالتوقيعات التي تم العثور عليها.

### ملاحظات

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### انظر أيضًا

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

يبحث عن التوقيعات في المستند باستخدام جميع خيارات البحث المتاحة ويصفي النتائج بناءً على الشرط المحدد.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| predicate | Func`2 | دالة الترشيح لتطبيقها على قائمة التوقيعات التي تم العثور عليها. |

### قيمة الإرجاع

يعيد قائمة من كائنات [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) التي تلبي الشرط المحدد.

### ملاحظات

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### انظر أيضًا

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
