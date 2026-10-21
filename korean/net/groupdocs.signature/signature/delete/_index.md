---
title: "Delete"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "문서에서 전달된 서명 BaseSignaturegroupdocs.signature.domain/basesignature를 삭제합니다."
type: docs
weight: 110
url: /ko/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

문서에서 전달된 서명 [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)를 삭제합니다.

```csharp
public bool Delete(BaseSignature signature)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 서명 | BaseSignature | 문서에서 제거될 서명 객체. |

### 반환 값

작업이 성공하면 true를 반환합니다.

### 비고

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또 보기

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

문서에서 전달된 서명 [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) 목록을 삭제합니다.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 서명 | List`1 | 문서에서 제거할 서명 목록. |

### 반환 값

성공적으로 삭제된 서명과 실패한 서명의 목록이 포함된 DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)를 반환합니다.

### 비고

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또 보기

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

문서에서 특정 유형의 서명 [`SignatureType`](../../../groupdocs.signature.domain/signaturetype)을 삭제합니다. Sign 메서드로 추가되고 서명 [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature)으로 표시된 서명만 제거됩니다. 지원되는 서명 유형은 다음과 같습니다: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signatureType | SignatureType | 문서에서 제거될 서명의 유형. |

### 반환 값

성공적으로 삭제된 서명과 실패한 서명의 목록이 포함된 DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)를 반환합니다.

### 비고

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또 보기

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

문서에서 특정 유형 목록의 서명 [`SignatureType`](../../../groupdocs.signature.domain/signaturetype)을 삭제합니다. Sign 메서드로 추가되고 서명 [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature)으로 표시된 서명만 제거됩니다. 지원되는 서명 유형은 다음과 같습니다: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signatureTypes | List`1 | 문서에서 제거될 서명 유형 목록. |

### 반환 값

성공적으로 삭제된 서명과 실패한 서명의 목록이 포함된 DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)를 반환합니다.

### 비고

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또 보기

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

문서에서 특정 서명 Id에 해당하는 서명을 삭제합니다.

```csharp
public bool Delete(string signatureId)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signatureId | String | 문서에서 제거될 서명의 ID입니다. |

### 반환 값

작업이 성공하면 true를 반환합니다.

### 비고

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또 보기

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

문서에서 전달된 서명 [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) 목록을 삭제합니다.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signatureIds | List`1 | 문서에서 제거될 서명의 식별자 목록입니다. |

### 반환 값

성공적으로 삭제된 서명과 실패한 서명의 목록이 포함된 DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult)를 반환합니다.

### 비고

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또 보기

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
