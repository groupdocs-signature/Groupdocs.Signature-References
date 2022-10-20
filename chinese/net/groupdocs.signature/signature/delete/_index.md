---
title: Delete
second_title: GroupDocs.Signature for .NET API 参考
description: 删除通过的签名BaseSignaturegroupdocs.signature.domain/basesignature来自文档.
type: docs
weight: 110
url: /zh/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

删除通过的签名[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)来自文档.

```csharp
public bool Delete(BaseSignature signature)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signature | BaseSignature | 要从文档中删除的签名对象。 |

### 返回值

如果操作成功，则返回 true。

### 评论

**学到更多**

* 更多关于如何在 C# 中从文档中删除电子签名： [如何使用 GroupDocs.Signature 从文档中删除电子签名](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* 删除文档电子签名的高级用例： [如何在 C# 中从文档中删除不同类型的电子签名](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 也可以看看

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

删除通过的签名列表[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)来自文档.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signatures | List`1 | 要从文档中删除的签名列表。 |

### 返回值

返回删除结果[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)包含成功删除的签名和失败的签名列表。

### 评论

**学到更多**

* 更多关于如何在 C# 中从文档中删除电子签名： [如何使用 GroupDocs.Signature 从文档中删除电子签名](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* 删除文档电子签名的高级用例： [如何在 C# 中从文档中删除不同类型的电子签名](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 也可以看看

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

删除特定类型的签名[`SignatureType`](../../../groupdocs.signature.domain/signaturetype)来自文档。 仅由 Sign 方法添加并标记为 Signatures 的签名[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature)将被删除。 支持以下签名类型：文本、图像、数字、条形码、二维码

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signatureType | SignatureType | 要从文档中删除的签名类型。 |

### 返回值

返回删除结果[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)包含成功删除的签名和失败的签名列表。

### 评论

**学到更多**

* 更多关于如何在 C# 中从文档中删除电子签名： [如何使用 GroupDocs.Signature 从文档中删除具有特定类型的电子签名](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* 删除文档电子签名的高级用例： [如何在 C# 中从文档中删除不同类型的电子签名](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 也可以看看

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

删除特定类型列表的签名[`SignatureType`](../../../groupdocs.signature.domain/signaturetype)来自文档。 仅由 Sign 方法添加并标记为 Signatures 的签名[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature)将被删除。 支持以下签名类型：文本、图像、数字、条形码、二维码

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signatureTypes | List`1 | 要从文档中删除的签名类型列表。 |

### 返回值

返回删除结果[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)包含成功删除的签名和失败的签名列表。

### 评论

**学到更多**

* 更多关于如何在 C# 中从文档中删除电子签名： [如何使用 GroupDocs.Signature 从文档中删除具有特定类型的电子签名](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* 删除文档电子签名的高级用例： [如何在 C# 中从文档中删除不同类型的电子签名](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 也可以看看

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

按其特定签名 ID 从文档中删除签名。

```csharp
public bool Delete(string signatureId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signatureId | String | 要从文档中删除的签名的 ID。 |

### 返回值

如果操作成功，则返回 true。

### 评论

**学到更多**

* 更多关于如何在 C# 中从文档中删除电子签名： [如何使用 GroupDocs.Signature 从文档中删除电子签名](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* 删除文档电子签名的高级用例： [如何在 C# 中从文档中删除不同类型的电子签名](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 也可以看看

* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

删除通过的签名列表[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)来自文档.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signatureIds | List`1 | 要从文档中删除的签名的标识符列表。 |

### 返回值

返回删除结果[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)包含成功删除的签名和失败的签名列表。

### 评论

**学到更多**

* 更多关于如何在 C# 中从文档中删除电子签名： [如何使用 GroupDocs.Signature 从文档中删除电子签名](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* 删除文档电子签名的高级用例： [如何在 C# 中从文档中删除不同类型的电子签名](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 也可以看看

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
