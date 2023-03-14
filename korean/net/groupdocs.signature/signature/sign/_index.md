---
title: Sign
second_title: .NET API 참조용 GroupDocs.Signature
description: 다음으로 문서에 서명SignOptionsgroupdocs.signature.options/signoptions 결과를 스트림에 저장합니다.
type: docs
weight: 160
url: /ko/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

다음으로 문서에 서명[`SignOptions`](../../../groupdocs.signature.options/signoptions) 결과를 스트림에 저장합니다.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 출력 문서 스트림입니다. |
| signOptions | SignOptions | 서명 옵션. |

### 반환 값

인스턴스를 반환합니다.[`SignResult`](../../../groupdocs.signature.domain/signresult) 새로 생성된 서명 목록과 함께.

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 전자 서명 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 전자 서명 유형](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 에서 문서에 전자 서명하는 방법에 대한 추가 정보[GroupDocs.Signature를 사용하여 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/Signing)

### 또한보십시오

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

다음으로 문서에 서명[`SignOptions`](../../../groupdocs.signature.options/signoptions)미리 정의된 스트림에 결과를 저장합니다.[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 출력 문서 스트림입니다. |
| signOptions | SignOptions | 서명 옵션. |
| saveOptions | SaveOptions | 저장 옵션. |

### 반환 값

인스턴스를 반환합니다.[`SignResult`](../../../groupdocs.signature.domain/signresult) 새로 생성된 서명 목록과 함께.

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 전자 서명 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 전자 서명 유형](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 에서 문서에 전자 서명하는 방법에 대한 추가 정보[GroupDocs.Signature를 사용하여 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/Signing)
* 전자 서명된 문서를 저장하고 저장 프로세스를 사용자 지정하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 저장할 때 전자 서명된 문서를 사용자 정의하는 방법](https://docs.groupdocs.com/display/signaturenet/Saving)

### 또한보십시오

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

컬렉션이 포함된 서명 문서[`SignOptions`](../../../groupdocs.signature.options/signoptions) 결과를 스트림에 저장합니다.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 출력 문서 스트림입니다. |
| signOptionsList | List`1 | 서명 옵션 목록입니다. |

### 반환 값

인스턴스를 반환합니다.[`SignResult`](../../../groupdocs.signature.domain/signresult) 새로 생성된 서명 목록과 함께.

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 전자 서명 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 전자 서명 유형](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 에서 문서에 전자 서명하는 방법에 대한 추가 정보[GroupDocs.Signature를 사용하여 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/Signing)

### 또한보십시오

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

컬렉션이 포함된 서명 문서[`SignOptions`](../../../groupdocs.signature.options/signoptions)미리 정의된 스트림에 결과를 저장합니다.[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 출력 문서 스트림입니다. |
| signOptionsList | List`1 | 서명 옵션 목록입니다. |
| saveOptions | SaveOptions | 저장 옵션. |

### 반환 값

인스턴스를 반환합니다.[`SignResult`](../../../groupdocs.signature.domain/signresult) 새로 생성된 서명 목록과 함께.

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 전자 서명 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 전자 서명 유형](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 에서 문서에 전자 서명하는 방법에 대한 추가 정보[GroupDocs.Signature를 사용하여 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/Signing)
* 전자 서명된 문서를 저장하고 저장 프로세스를 사용자 지정하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 저장할 때 전자 서명된 문서를 사용자 정의하는 방법](https://docs.groupdocs.com/display/signaturenet/Saving)

### 또한보십시오

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

다음으로 문서에 서명[`SignOptions`](../../../groupdocs.signature.options/signoptions) 지정된 파일 경로에 결과를 저장합니다.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 출력 파일 경로입니다. |
| signOptions | SignOptions | 서명 옵션. |

### 반환 값

인스턴스를 반환합니다.[`SignResult`](../../../groupdocs.signature.domain/signresult) 새로 생성된 서명 목록과 함께.

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 전자 서명 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 전자 서명 유형](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 에서 문서에 전자 서명하는 방법에 대한 추가 정보[GroupDocs.Signature를 사용하여 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/Signing)

### 또한보십시오

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

다음으로 문서에 서명[`SignOptions`](../../../groupdocs.signature.options/signoptions) 미리 정의된 지정된 파일 경로에 결과를 저장합니다.[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 출력 파일 경로입니다. |
| signOptions | SignOptions | 서명 옵션. |
| saveOptions | SaveOptions | 저장 옵션. |

### 반환 값

인스턴스를 반환합니다.[`SignResult`](../../../groupdocs.signature.domain/signresult) 새로 생성된 서명 목록과 함께.

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 전자 서명 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 전자 서명 유형](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 에서 문서에 전자 서명하는 방법에 대한 추가 정보[GroupDocs.Signature를 사용하여 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/Signing)
* 전자 서명된 문서를 저장하고 저장 프로세스를 사용자 지정하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 저장할 때 전자 서명된 문서를 사용자 정의하는 방법](https://docs.groupdocs.com/display/signaturenet/Saving)

### 또한보십시오

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

컬렉션이 포함된 서명 문서[`SignOptions`](../../../groupdocs.signature.options/signoptions) 지정된 파일 경로에 결과를 저장합니다.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 출력 파일 경로입니다. |
| signOptionsList | List`1 | 서명 옵션 목록입니다. |

### 반환 값

인스턴스를 반환합니다.[`SignResult`](../../../groupdocs.signature.domain/signresult) 새로 생성된 서명 목록과 함께.

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 전자 서명 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 전자 서명 유형](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 에서 문서에 전자 서명하는 방법에 대한 추가 정보[GroupDocs.Signature를 사용하여 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/Signing)

### 또한보십시오

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

컬렉션이 포함된 서명 문서[`SignOptions`](../../../groupdocs.signature.options/signoptions) 미리 정의된 지정된 파일 경로에 결과를 저장합니다.[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 출력 파일 경로입니다. |
| signOptionsList | List`1 | 서명 옵션 목록입니다. |
| saveOptions | SaveOptions | 저장 옵션. |

### 반환 값

인스턴스를 반환합니다.[`SignResult`](../../../groupdocs.signature.domain/signresult) 새로 생성된 서명 목록과 함께.

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 전자 서명 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 전자 서명 유형](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 에서 문서에 전자 서명하는 방법에 대한 추가 정보[GroupDocs.Signature를 사용하여 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/Signing)
* 전자 서명된 문서를 저장하고 저장 프로세스를 사용자 지정하는 방법에 대한 추가 정보: [GroupDocs.Signature를 사용하여 저장할 때 전자 서명된 문서를 사용자 정의하는 방법](https://docs.groupdocs.com/display/signaturenet/Saving)

### 또한보십시오

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 네임스페이스 [GroupDocs.Signature](../../signature)
* 집회 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
