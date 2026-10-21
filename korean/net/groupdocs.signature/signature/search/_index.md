---
title: "검색"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "문서에서 SearchOptionsgroupdocs.signature.options/searchoptions 목록을 사용하여 서명을 검색합니다."
type: docs
weight: 150
url: /ko/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

문서에서 [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) 목록을 사용하여 서명을 검색합니다.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchOptionsList | List`1 | 검색 옵션 컬렉션입니다. |

### 반환 값

찾은 서명의 목록과 함께 [`SearchResult`](../../../groupdocs.signature.domain/searchresult) 인스턴스를 반환합니다.

### 비고

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 또 보기

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

제공된 검색 옵션을 사용하여 문서에서 서명을 검색하고 지정된 predicate에 따라 결과를 필터링합니다.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchOptionsList | List`1 | [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) 인스턴스 목록으로, 서명을 검색하기 위한 기준을 정의합니다. |
| predicate | Func`2 | 찾은 서명 목록에 적용할 필터 프레디케이트입니다. |

### 반환 값

지정된 검색 옵션과 프레디케이트를 만족하는 서명을 포함하는 [`SearchResult`](../../../groupdocs.signature.domain/searchresult)를 반환합니다.

### 비고

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 또 보기

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

문서에서 [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) 옵션을 사용하여 서명을 검색합니다.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| searchOptions | SearchOptions | 검색 옵션입니다. |

### 반환 값

찾은 서명 목록을 반환합니다.

### 비고

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 또 보기

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

문서에서 [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) 값을 사용하여 정확한 유형의 서명을 검색합니다.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signatureType | SignatureType | 검색할 서명의 유형입니다. |

### 반환 값

정확한 유형의 찾은 서명 목록을 반환합니다.

### 비고

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 또 보기

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

문서에서 [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) 값을 사용하여 지정된 서명 유형을 검색합니다.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signatureTypes | SignatureType[] | 찾을 서명의 하나 또는 여러 유형. |

### 반환 값

찾은 서명의 목록이 포함된 [`SearchResult`](../../../groupdocs.signature.domain/searchresult) 인스턴스를 반환합니다.

### 비고

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 또 보기

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

문서에서 모든 사용 가능한 검색 옵션을 사용하여 서명을 검색하고 지정된 프레디케이트에 따라 결과를 필터링합니다.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| predicate | Func`2 | 찾은 서명 목록에 적용할 필터 프레디케이트입니다. |

### 반환 값

제공된 조건을 만족하는 [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) 인스턴스 목록을 반환합니다.

### 비고

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 또 보기

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
