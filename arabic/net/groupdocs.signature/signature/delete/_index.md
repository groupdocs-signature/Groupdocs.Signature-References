---
title: "Delete"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يحذف التوقيع الممرّر BaseSignaturegroupdocs.signature.domain/basesignature من المستند."
type: docs
weight: 110
url: /ar/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

يحذف التوقيع الممرّر [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) من المستند.

```csharp
public bool Delete(BaseSignature signature)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| توقيع | BaseSignature | كائن التوقيع الذي سيُزال من المستند. |

### قيمة الإرجاع

يعيد true إذا نجحت العملية.

### ملاحظات

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### انظر أيضًا

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

يحذف القائمة الممرّرة من التوقيعات [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) من المستند.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التوقيعات | List`1 | قائمة التوقيعات لإزالتها من المستند. |

### قيمة الإرجاع

يعيد DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) مع قائمة بالتوقيعات التي تم حذفها بنجاح وتلك التي فشلت.

### ملاحظات

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### انظر أيضًا

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

يحذف التوقيعات من النوع المحدد [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) من المستند. سيتم إزالة فقط التوقيعات التي أضيفت بواسطة طريقة Sign وتم تمييزها كـ Signatures [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature). الأنواع التالية من التوقيعات مدعومة: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureType | SignatureType | نوع التوقيعات التي ستُحذف من المستند. |

### قيمة الإرجاع

يعيد DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) مع قائمة بالتوقيعات التي تم حذفها بنجاح وتلك التي فشلت.

### ملاحظات

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### انظر أيضًا

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

يحذف التوقيعات من قائمة الأنواع المحددة [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) من المستند. سيتم إزالة فقط التوقيعات التي أضيفت بواسطة طريقة Sign وتم تمييزها كـ Signatures [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature). الأنواع التالية من التوقيعات مدعومة: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureTypes | List`1 | قائمة أنواع التوقيعات التي ستُحذف من المستند. |

### قيمة الإرجاع

يعيد DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) مع قائمة بالتوقيعات التي تم حذفها بنجاح وتلك التي فشلت.

### ملاحظات

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### انظر أيضًا

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

يحذف التوقيع بواسطة معرف توقيعه المحدد من المستند.

```csharp
public bool Delete(string signatureId)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureId | String | معرّف Id للتوقيع الذي سيتم إزالته من المستند. |

### قيمة الإرجاع

يعيد true إذا نجحت العملية.

### ملاحظات

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### انظر أيضًا

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

يحذف القائمة الممرّرة من التوقيعات [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) من المستند.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| signatureIds | List`1 | قائمة بمعرّفات التوقيعات التي سيتم إزالتها من المستند. |

### قيمة الإرجاع

يعيد DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) مع قائمة بالتوقيعات التي تم حذفها بنجاح وتلك التي فشلت.

### ملاحظات

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### انظر أيضًا

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
