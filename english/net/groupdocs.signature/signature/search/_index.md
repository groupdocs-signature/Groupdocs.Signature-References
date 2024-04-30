---
title: Search
second_title: GroupDocs.Signature for .NET API Reference
description: Searches for signatures in a document by SearchOptionsgroupdocs.signature.options/searchoptions list.
type: docs
weight: 150
url: /net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Searches for signatures in a document by [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) list.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Type | Description |
| --- | --- | --- |
| searchOptionsList | List`1 | The search options collection. |

### Return Value

Returns instance of [`SearchResult`](../../../groupdocs.signature.domain/searchresult) with list of found Signatures.

### Remarks

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### See Also

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Searches for signatures in a document by [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) options.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Type | Description |
| --- | --- | --- |
| searchOptions | SearchOptions | The search options. |

### Return Value

Returns the list of signatures found.

### Remarks

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### See Also

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Searches for exact type of signatures in the document by [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) value.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Type | Description |
| --- | --- | --- |
| signatureType | SignatureType | The type of signatures to search. |

### Return Value

Returns the list of found signatures with exact type.

### Remarks

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### See Also

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Searches for specified signature types in the document by [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) value.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signatureTypes | SignatureType[] | One or several types of signatures to find. |

### Return Value

Returns instance of [`SearchResult`](../../../groupdocs.signature.domain/searchresult) with list of found signatures.

### Remarks

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### See Also

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
