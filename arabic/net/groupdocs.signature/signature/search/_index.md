---
title: Search
second_title: GroupDocs.Signature لمرجع .NET API
description: يبحث عن التوقيعات في مستند بواسطةSearchOptionsgroupdocs.signature.options/searchoptions القائمة .
type: docs
weight: 150
url: /ar/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

يبحث عن التوقيعات في مستند بواسطة[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) القائمة .

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| searchOptionsList | List`1 | مجموعة خيارات البحث. |

### قيمة الإرجاع

إرجاع مثيل[`SearchResult`](../../../groupdocs.signature.domain/searchresult) مع قائمة التوقيعات التي تم العثور عليها.

### ملاحظات

**يتعلم أكثر**

* المزيد حول البحث في التوقيعات الإلكترونية في المستندات باستخدام GroupDocs. التوقيع: [كيفية البحث عن التوقيعات الإلكترونية داخل المستند باستخدام C #](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* المزيد حول البحث في التوقيعات الإلكترونية التي تعتمد على نوع eSign: [حالات الاستخدام المتقدمة للتوقيعات الإلكترونية البحث باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### أنظر أيضا

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

يبحث عن التوقيعات في مستند بواسطة[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) خيارات.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| searchOptions | SearchOptions | خيارات البحث. |

### قيمة الإرجاع

إرجاع قائمة التوقيعات التي تم العثور عليها.

### ملاحظات

**يتعلم أكثر**

* المزيد حول البحث في التوقيعات الإلكترونية في المستندات باستخدام GroupDocs. التوقيع: [كيفية البحث عن التوقيعات الإلكترونية داخل المستند باستخدام C #](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* المزيد حول البحث في التوقيعات الإلكترونية التي تعتمد على نوع eSign: [حالات الاستخدام المتقدمة للتوقيعات الإلكترونية البحث باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### أنظر أيضا

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

يبحث عن نوع التوقيع الدقيق في المستند بواسطة[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) القيمة .

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| signatureType | SignatureType | نوع التوقيعات للبحث. |

### قيمة الإرجاع

إرجاع قائمة التوقيعات التي تم العثور عليها بالنوع الدقيق.

### ملاحظات

**يتعلم أكثر**

* المزيد حول البحث في التوقيعات الإلكترونية في المستندات باستخدام GroupDocs. التوقيع: [كيفية البحث عن التوقيعات الإلكترونية داخل المستند باستخدام C #](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* المزيد حول البحث في التوقيعات الإلكترونية التي تعتمد على نوع eSign: [حالات الاستخدام المتقدمة للتوقيعات الإلكترونية البحث باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### أنظر أيضا

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

يبحث عن أنواع التوقيع المحددة في المستند بواسطة[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) القيمة .

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| signatureTypes | SignatureType[] | واحد أو عدة أنواع من التوقيعات للبحث عنها. |

### قيمة الإرجاع

إرجاع مثيل[`SearchResult`](../../../groupdocs.signature.domain/searchresult) مع قائمة التوقيعات التي تم العثور عليها.

### ملاحظات

**يتعلم أكثر**

* المزيد حول البحث في التوقيعات الإلكترونية في المستندات باستخدام GroupDocs. التوقيع: [كيفية البحث عن التوقيعات الإلكترونية داخل المستند باستخدام C #](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* المزيد حول البحث في التوقيعات الإلكترونية التي تعتمد على نوع eSign: [حالات الاستخدام المتقدمة للتوقيعات الإلكترونية البحث باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### أنظر أيضا

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
