---
title: "搜索"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "在文档中通过 SearchOptionsgroupdocs.signature.options/searchoptions 列表搜索签名。"
type: docs
weight: 150
url: /zh/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

在文档中通过 [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) 列表搜索签名。

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchOptionsList | List`1 | 搜索选项集合。 |

### 返回值

返回 [`SearchResult`](../../../groupdocs.signature.domain/searchresult) 实例，其中包含找到的签名列表。

### 备注

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 另请参见

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

使用提供的搜索选项在文档中搜索签名，并根据指定的谓词过滤结果。

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchOptionsList | List`1 | 一个 [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) 实例列表，用于定义搜索签名的条件。 |
| predicate | Func`2 | 用于对找到的签名列表进行过滤的谓词。 |

### 返回值

返回一个 [`SearchResult`](../../../groupdocs.signature.domain/searchresult)，其中包含匹配指定搜索选项并满足谓词的签名。

### 备注

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 另请参见

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

在文档中通过 [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) 选项搜索签名。

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchOptions | SearchOptions | 搜索选项。 |

### 返回值

返回找到的签名列表。

### 备注

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 另请参见

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

在文档中通过 [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) 值搜索精确类型的签名。

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signatureType | SignatureType | 要搜索的签名类型。 |

### 返回值

返回具有精确类型的找到的签名列表。

### 备注

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 另请参见

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

在文档中通过 [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) 值搜索指定的签名类型。

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signatureTypes | SignatureType[] | 一个或多个要查找的签名类型。 |

### 返回值

返回 [`SearchResult`](../../../groupdocs.signature.domain/searchresult) 的实例，其中包含找到的签名列表。

### 备注

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 另请参见

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

使用所有可用的搜索选项在文档中搜索签名，并根据指定的谓词过滤结果。

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| predicate | Func`2 | 用于对找到的签名列表进行过滤的谓词。 |

### 返回值

返回满足提供的谓词的 [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) 实例列表。

### 备注

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 另请参见

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
