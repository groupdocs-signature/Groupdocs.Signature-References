---
title: "Delete"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "从文档中删除传入的签名 BaseSignaturegroupdocs.signature.domain/basesignature。"
type: docs
weight: 110
url: /zh/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

从文档中删除传入的签名 [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)。

```csharp
public bool Delete(BaseSignature signature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 签名 | BaseSignature | 要从文档中移除的签名对象。 |

### 返回值

如果操作成功，则返回 true。

### 备注

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 另请参见

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

从文档中删除传入的签名列表 [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)。

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 签名 | List`1 | 要从文档中移除的签名列表。 |

### 返回值

返回 DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)，其中包含成功删除的签名列表和失败的签名。

### 备注

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 另请参见

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

从文档中删除特定类型的签名 [`SignatureType`](../../../groupdocs.signature.domain/signaturetype)。仅删除由 Sign 方法添加并标记为签名 [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) 的签名。支持以下签名类型：Text、Image、Digital、Barcode、QR-Code。

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signatureType | SignatureType | 要从文档中移除的签名类型。 |

### 返回值

返回 DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)，其中包含成功删除的签名列表和失败的签名。

### 备注

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 另请参见

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

从文档中删除特定类型列表的签名 [`SignatureType`](../../../groupdocs.signature.domain/signaturetype)。仅删除由 Sign 方法添加并标记为签名 [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) 的签名。支持以下签名类型：Text、Image、Digital、Barcode、QR-Code。

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signatureTypes | List`1 | 要从文档中移除的签名类型列表。 |

### 返回值

返回 DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)，其中包含成功删除的签名列表和失败的签名。

### 备注

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 另请参见

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

从文档中删除具有特定签名 Id 的签名。

```csharp
public bool Delete(string signatureId)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signatureId | String | 要从文档中移除的签名的 Id。 |

### 返回值

如果操作成功，则返回 true。

### 备注

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 另请参见

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

从文档中删除传入的签名列表 [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)。

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signatureIds | List`1 | 要从文档中移除的签名标识符列表。 |

### 返回值

返回 DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)，其中包含成功删除的签名列表和失败的签名。

### 备注

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 另请参见

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
