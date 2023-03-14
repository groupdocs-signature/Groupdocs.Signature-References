---
title: Delete
second_title: GroupDocs.Signature for .NET API リファレンス
description: 渡された署名を削除しますBaseSignaturegroupdocs.signature.domain/basesignatureドキュメントから.
type: docs
weight: 110
url: /ja/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

渡された署名を削除します[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)ドキュメントから.

```csharp
public bool Delete(BaseSignature signature)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| signature | BaseSignature | ドキュメントから削除する署名オブジェクト。 |

### 戻り値

操作が成功した場合は true を返します。

### 備考

**もっと詳しく知る**

* C# でドキュメントから電子署名を削除する方法の詳細: [GroupDocs.Signature を使用して文書から電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* ドキュメントの電子署名を削除する高度な使用例: [C# でドキュメントからさまざまな種類の電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

渡された署名のリストを削除します[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)ドキュメントから.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| signatures | List`1 | ドキュメントから削除する署名のリスト。 |

### 戻り値

DeleteResult を返します[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)正常に削除された署名と失敗した署名のリスト。

### 備考

**もっと詳しく知る**

* C# でドキュメントから電子署名を削除する方法の詳細: [GroupDocs.Signature を使用して文書から電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* ドキュメントの電子署名を削除する高度な使用例: [C# でドキュメントからさまざまな種類の電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

特定のタイプの署名を削除します[`SignatureType`](../../../groupdocs.signature.domain/signaturetype)ドキュメントから. Sign メソッドによって追加され、Signatures としてマークされた署名のみ[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) 次の署名タイプがサポートされています: テキスト、画像、デジタル、バーコード、QR コード

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| signatureType | SignatureType | ドキュメントから削除する署名のタイプ。 |

### 戻り値

DeleteResult を返します[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)正常に削除された署名と失敗した署名のリスト。

### 備考

**もっと詳しく知る**

* C# でドキュメントから電子署名を削除する方法の詳細: [GroupDocs.Signature を使用してドキュメントから特定の種類の電子署名を削除する方法](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* ドキュメントの電子署名を削除する高度な使用例: [C# でドキュメントからさまざまな種類の電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

特定のタイプ リストの署名を削除します[`SignatureType`](../../../groupdocs.signature.domain/signaturetype)ドキュメントから. Sign メソッドによって追加され、Signatures としてマークされた署名のみ[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) 次の署名タイプがサポートされています: テキスト、画像、デジタル、バーコード、QR コード

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| signatureTypes | List`1 | ドキュメントから削除する署名タイプのリスト。 |

### 戻り値

DeleteResult を返します[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)正常に削除された署名と失敗した署名のリスト。

### 備考

**もっと詳しく知る**

* C# でドキュメントから電子署名を削除する方法の詳細: [GroupDocs.Signature を使用してドキュメントから特定の種類の電子署名を削除する方法](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* ドキュメントの電子署名を削除する高度な使用例: [C# でドキュメントからさまざまな種類の電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

特定の署名 ID で署名をドキュメントから削除します。

```csharp
public bool Delete(string signatureId)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| signatureId | String | ドキュメントから削除する署名の ID。 |

### 戻り値

操作が成功した場合は true を返します。

### 備考

**もっと詳しく知る**

* C# でドキュメントから電子署名を削除する方法の詳細: [GroupDocs.Signature を使用して文書から電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* ドキュメントの電子署名を削除する高度な使用例: [C# でドキュメントからさまざまな種類の電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

渡された署名のリストを削除します[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)ドキュメントから.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| signatureIds | List`1 | ドキュメントから削除する署名の識別子のリスト。 |

### 戻り値

DeleteResult を返します[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)正常に削除された署名と失敗した署名のリスト。

### 備考

**もっと詳しく知る**

* C# でドキュメントから電子署名を削除する方法の詳細: [GroupDocs.Signature を使用して文書から電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* ドキュメントの電子署名を削除する高度な使用例: [C# でドキュメントからさまざまな種類の電子署名を削除する方法](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 関連項目

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
