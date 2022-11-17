---
title: Delete
second_title: GroupDocs.Signature لمرجع .NET API
description: حذف التوقيع الذي تم تمريرهBaseSignaturegroupdocs.signature.domain/basesignature من الوثيقة.
type: docs
weight: 110
url: /ar/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

حذف التوقيع الذي تم تمريره[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) من الوثيقة.

```csharp
public bool Delete(BaseSignature signature)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| signature | BaseSignature | كائن التوقيع المراد إزالته من المستند. |

### قيمة الإرجاع

يعود صحيحا إذا كانت العملية ناجحة.

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية حذف التوقيع الإلكتروني من المستند في C #: [كيفية حذف التوقيع الإلكتروني من المستند باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* حالات الاستخدام المتقدمة لحذف التوقيعات الإلكترونية للمستند: [كيفية حذف أنواع مختلفة من التوقيعات الإلكترونية من المستند في C #](https://docs.groupdocs.com/display/signaturenet/Deleting)

### أنظر أيضا

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

حذف قائمة التوقيعات التي تم تمريرها[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) من الوثيقة.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| signatures | List`1 | قائمة التوقيعات المطلوب إزالتها من المستند. |

### قيمة الإرجاع

إرجاع DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) مع قائمة التوقيعات المحذوفة بنجاح والتوقيعات الفاشلة.

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية حذف التوقيع الإلكتروني من المستند في C #: [كيفية حذف التوقيع الإلكتروني من المستند باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* حالات الاستخدام المتقدمة لحذف التوقيعات الإلكترونية للمستند: [كيفية حذف أنواع مختلفة من التوقيعات الإلكترونية من المستند في C #](https://docs.groupdocs.com/display/signaturenet/Deleting)

### أنظر أيضا

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

حذف التوقيعات من نوع معين[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) من المستند . التوقيعات التي تمت إضافتها بواسطة طريقة التوقيع فقط وتم تمييزها على أنها تواقيع[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) أنواع التوقيعات التالية مدعومة: نص ، صورة ، رقمي ، باركود ، QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| signatureType | SignatureType | نوع التوقيعات المراد إزالتها من المستند. |

### قيمة الإرجاع

إرجاع DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) مع قائمة التوقيعات المحذوفة بنجاح والتوقيعات الفاشلة.

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية حذف التوقيع الإلكتروني من المستند في C #: [كيفية حذف التوقيعات الإلكترونية بنوع معين من المستند باستخدام GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* حالات الاستخدام المتقدمة لحذف التوقيعات الإلكترونية للمستند: [كيفية حذف أنواع مختلفة من التوقيعات الإلكترونية من المستند في C #](https://docs.groupdocs.com/display/signaturenet/Deleting)

### أنظر أيضا

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

حذف تواقيع قائمة الأنواع المعينة[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) من المستند . التوقيعات التي تمت إضافتها بواسطة طريقة التوقيع فقط وتم تمييزها على أنها تواقيع[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) أنواع التوقيعات التالية مدعومة: نص ، صورة ، رقمي ، باركود ، QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| signatureTypes | List`1 | قائمة أنواع التواقيع المراد إزالتها من المستند. |

### قيمة الإرجاع

إرجاع DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) مع قائمة التوقيعات المحذوفة بنجاح والتوقيعات الفاشلة.

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية حذف التوقيع الإلكتروني من المستند في C #: [كيفية حذف التوقيعات الإلكترونية بنوع معين من المستند باستخدام GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* حالات الاستخدام المتقدمة لحذف التوقيعات الإلكترونية للمستند: [كيفية حذف أنواع مختلفة من التوقيعات الإلكترونية من المستند في C #](https://docs.groupdocs.com/display/signaturenet/Deleting)

### أنظر أيضا

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

حذف التوقيع بمعرف التوقيع المحدد الخاص به من المستند.

```csharp
public bool Delete(string signatureId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| signatureId | String | معرّف التوقيع المراد إزالته من المستند. |

### قيمة الإرجاع

يعود صحيحا إذا كانت العملية ناجحة.

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية حذف التوقيع الإلكتروني من المستند في C #: [كيفية حذف التوقيع الإلكتروني من المستند باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* حالات الاستخدام المتقدمة لحذف التوقيعات الإلكترونية للمستند: [كيفية حذف أنواع مختلفة من التوقيعات الإلكترونية من المستند في C #](https://docs.groupdocs.com/display/signaturenet/Deleting)

### أنظر أيضا

* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

حذف قائمة التوقيعات التي تم تمريرها[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) من الوثيقة.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| signatureIds | List`1 | قائمة معرفات التواقيع المراد إزالتها من المستند. |

### قيمة الإرجاع

إرجاع DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) مع قائمة التوقيعات المحذوفة بنجاح والتوقيعات الفاشلة.

### ملاحظات

**يتعلم أكثر**

* المزيد حول كيفية حذف التوقيع الإلكتروني من المستند في C #: [كيفية حذف التوقيع الإلكتروني من المستند باستخدام GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* حالات الاستخدام المتقدمة لحذف التوقيعات الإلكترونية للمستند: [كيفية حذف أنواع مختلفة من التوقيعات الإلكترونية من المستند في C #](https://docs.groupdocs.com/display/signaturenet/Deleting)

### أنظر أيضا

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* مساحة الاسم [GroupDocs.Signature](../../signature)
* المجسم [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
