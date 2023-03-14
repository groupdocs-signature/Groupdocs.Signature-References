---
title: Delete
second_title: .NET API 참조용 GroupDocs.Signature
description: 전달된 서명을 삭제합니다.BaseSignaturegroupdocs.signature.domain/basesignature 문서에서.
type: docs
weight: 110
url: /ko/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

전달된 서명을 삭제합니다.[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) 문서에서.

```csharp
public bool Delete(BaseSignature signature)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signature | BaseSignature | 문서에서 제거할 서명 개체입니다. |

### 반환 값

작업이 성공하면 true를 반환합니다.

### 비고

**더 알아보기**

* C#의 문서에서 전자 서명을 삭제하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 문서에서 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* 문서 전자 서명 삭제의 고급 사용 사례: [C#의 문서에서 다양한 유형의 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또한보십시오

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

전달된 서명 목록을 삭제합니다.[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) 문서에서.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signatures | List`1 | 문서에서 제거할 서명 목록입니다. |

### 반환 값

삭제 결과 반환[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) 성공적으로 삭제된 서명 및 실패한 서명 목록이 포함됩니다.

### 비고

**더 알아보기**

* C#의 문서에서 전자 서명을 삭제하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 문서에서 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* 문서 전자 서명 삭제의 고급 사용 사례: [C#의 문서에서 다양한 유형의 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또한보십시오

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

특정 유형의 서명을 삭제합니다.[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) 문서에서. 서명 방법으로 추가되고 서명으로 표시된 서명만[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) 제거됩니다. 다음 서명 유형이 지원됩니다: 텍스트, 이미지, 디지털, 바코드, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signatureType | SignatureType | 문서에서 제거할 서명 유형입니다. |

### 반환 값

삭제 결과 반환[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) 성공적으로 삭제된 서명 및 실패한 서명 목록이 포함됩니다.

### 비고

**더 알아보기**

* C#의 문서에서 전자 서명을 삭제하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 문서에서 특정 유형의 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* 문서 전자 서명 삭제의 고급 사용 사례: [C#의 문서에서 다양한 유형의 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또한보십시오

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

특정 유형 목록의 서명을 삭제합니다.[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) 문서에서. 서명 방법으로 추가되고 서명으로 표시된 서명만[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) 제거됩니다. 다음 서명 유형이 지원됩니다: 텍스트, 이미지, 디지털, 바코드, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signatureTypes | List`1 | 문서에서 제거할 서명 유형 목록입니다. |

### 반환 값

삭제 결과 반환[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) 성공적으로 삭제된 서명 및 실패한 서명 목록이 포함됩니다.

### 비고

**더 알아보기**

* C#의 문서에서 전자 서명을 삭제하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 문서에서 특정 유형의 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* 문서 전자 서명 삭제의 고급 사용 사례: [C#의 문서에서 다양한 유형의 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또한보십시오

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

문서에서 특정 서명 ID로 서명을 삭제합니다.

```csharp
public bool Delete(string signatureId)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signatureId | String | 문서에서 제거할 서명의 ID입니다. |

### 반환 값

작업이 성공하면 true를 반환합니다.

### 비고

**더 알아보기**

* C#의 문서에서 전자 서명을 삭제하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 문서에서 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* 문서 전자 서명 삭제의 고급 사용 사례: [C#의 문서에서 다양한 유형의 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또한보십시오

* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

전달된 서명 목록을 삭제합니다.[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) 문서에서.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signatureIds | List`1 | 문서에서 제거할 서명의 식별자 목록입니다. |

### 반환 값

삭제 결과 반환[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) 성공적으로 삭제된 서명 및 실패한 서명 목록이 포함됩니다.

### 비고

**더 알아보기**

* C#의 문서에서 전자 서명을 삭제하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 문서에서 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* 문서 전자 서명 삭제의 고급 사용 사례: [C#의 문서에서 다양한 유형의 전자 서명을 삭제하는 방법](https://docs.groupdocs.com/display/signaturenet/Deleting)

### 또한보십시오

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
