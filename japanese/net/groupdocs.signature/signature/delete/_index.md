---
title: "Delete"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "ドキュメントから渡された署名 BaseSignaturegroupdocs.signature.domain/basesignature を削除します。"
type: docs
weight: 110
url: /ja/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

ドキュメントから渡された署名[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)を削除します。

```csharp
public bool Delete(BaseSignature signature)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 署名 | BaseSignature | ドキュメントから削除される署名オブジェクト。 |

### 戻り値

操作が成功した場合に true を返します。

### 備考

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

ドキュメントから渡された署名[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)のリストを削除します。

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 署名 | List`1 | ドキュメントから削除する署名のリスト。 |

### 戻り値

削除に成功した署名と失敗した署名のリストを含むDeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) を返します。

### 備考

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

ドキュメントから特定のタイプの署名[`SignatureType`](../../../groupdocs.signature.domain/signaturetype)を削除します。Sign メソッドで追加され、署名[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature)としてマークされた署名のみが削除されます。サポートされている署名タイプは次のとおりです：Text、Image、Digital、Barcode、QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signatureType | SignatureType | ドキュメントから削除される署名のタイプ。 |

### 戻り値

削除に成功した署名と失敗した署名のリストを含むDeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) を返します。

### 備考

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

ドキュメントから特定のタイプリスト[`SignatureType`](../../../groupdocs.signature.domain/signaturetype)の署名を削除します。Sign メソッドで追加され、署名[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature)としてマークされた署名のみが削除されます。サポートされている署名タイプは次のとおりです：Text、Image、Digital、Barcode、QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signatureTypes | List`1 | ドキュメントから削除される署名タイプのリスト。 |

### 戻り値

削除に成功した署名と失敗した署名のリストを含むDeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) を返します。

### 備考

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

ドキュメントから特定の署名 Id による署名を削除します。

```csharp
public bool Delete(string signatureId)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signatureId | String | ドキュメントから削除される署名の Id。 |

### 戻り値

操作が成功した場合に true を返します。

### 備考

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

ドキュメントから渡された署名[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)のリストを削除します。

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signatureIds | List`1 | ドキュメントから削除される署名の識別子のリスト。 |

### 戻り値

削除に成功した署名と失敗した署名のリストを含むDeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) を返します。

### 備考

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
