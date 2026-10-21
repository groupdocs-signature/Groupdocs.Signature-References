---
title: "Sign"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "SignOptionsgroupdocs.signature.options/signoptions를 사용하여 문서에 서명하고 결과를 스트림에 저장합니다."
type: docs
weight: 160
url: /ko/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

[`SignOptions`](../../../groupdocs.signature.options/signoptions)를 사용하여 문서에 서명하고 결과를 스트림에 저장합니다.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| document | Stream | 출력 문서 스트림입니다. |
| signOptions | SignOptions | 서명 옵션입니다. |

### 반환 값

[`SignResult`](../../../groupdocs.signature.domain/signresult) 인스턴스를 반환하며, 새로 생성된 서명의 목록을 포함합니다.

### 비고

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 또 보기

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

[`SignOptions`](../../../groupdocs.signature.options/signoptions)를 사용하여 문서에 서명하고, 미리 정의된 [`SaveOptions`](../../../groupdocs.signature.options/saveoptions)와 함께 결과를 스트림에 저장합니다.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| document | Stream | 출력 문서 스트림입니다. |
| signOptions | SignOptions | 서명 옵션입니다. |
| saveOptions | SaveOptions | 저장 옵션입니다. |

### 반환 값

[`SignResult`](../../../groupdocs.signature.domain/signresult) 인스턴스를 반환하며, 새로 생성된 서명의 목록을 포함합니다.

### 비고

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 또 보기

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) 컬렉션을 사용하여 문서에 서명하고 결과를 스트림에 저장합니다.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| document | Stream | 출력 문서 스트림입니다. |
| signOptionsList | List`1 | 서명 옵션 목록. |

### 반환 값

[`SignResult`](../../../groupdocs.signature.domain/signresult) 인스턴스를 반환하며, 새로 생성된 서명의 목록을 포함합니다.

### 비고

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 또 보기

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

문서를 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 컬렉션으로 서명하고, 미리 정의된 [`SaveOptions`](../../../groupdocs.signature.options/saveoptions)와 함께 결과를 스트림에 저장합니다.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| document | Stream | 출력 문서 스트림입니다. |
| signOptionsList | List`1 | 서명 옵션 목록. |
| saveOptions | SaveOptions | 저장 옵션입니다. |

### 반환 값

[`SignResult`](../../../groupdocs.signature.domain/signresult) 인스턴스를 반환하며, 새로 생성된 서명의 목록을 포함합니다.

### 비고

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 또 보기

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

문서를 [`SignOptions`](../../../groupdocs.signature.options/signoptions)으로 서명하고, 지정된 파일 경로에 결과를 저장합니다.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 출력 파일 경로입니다. |
| signOptions | SignOptions | 서명 옵션입니다. |

### 반환 값

[`SignResult`](../../../groupdocs.signature.domain/signresult) 인스턴스를 반환하며, 새로 생성된 서명의 목록을 포함합니다.

### 비고

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 또 보기

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

문서를 [`SignOptions`](../../../groupdocs.signature.options/signoptions)으로 서명하고, 미리 정의된 [`SaveOptions`](../../../groupdocs.signature.options/saveoptions)와 함께 지정된 파일 경로에 결과를 저장합니다.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 출력 파일 경로입니다. |
| signOptions | SignOptions | 서명 옵션입니다. |
| saveOptions | SaveOptions | 저장 옵션입니다. |

### 반환 값

[`SignResult`](../../../groupdocs.signature.domain/signresult) 인스턴스를 반환하며, 새로 생성된 서명의 목록을 포함합니다.

### 비고

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 또 보기

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

문서를 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 컬렉션으로 서명하고, 지정된 파일 경로에 결과를 저장합니다.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 출력 파일 경로입니다. |
| signOptionsList | List`1 | 서명 옵션 목록. |

### 반환 값

[`SignResult`](../../../groupdocs.signature.domain/signresult) 인스턴스를 반환하며, 새로 생성된 서명의 목록을 포함합니다.

### 비고

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 또 보기

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

문서를 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 컬렉션으로 서명하고, 미리 정의된 [`SaveOptions`](../../../groupdocs.signature.options/saveoptions)와 함께 지정된 파일 경로에 결과를 저장합니다.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 출력 파일 경로입니다. |
| signOptionsList | List`1 | 서명 옵션 목록. |
| saveOptions | SaveOptions | 저장 옵션입니다. |

### 반환 값

[`SignResult`](../../../groupdocs.signature.domain/signresult) 인스턴스를 반환하며, 새로 생성된 서명의 목록을 포함합니다.

### 비고

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 또 보기

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
