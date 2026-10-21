---
title: "検索"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "ドキュメント内の署名を SearchOptionsgroupdocs.signature.options/searchoptions リストで検索します。"
type: docs
weight: 150
url: /ja/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

ドキュメント内の署名を [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) リストで検索します。

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| searchOptionsList | List`1 | 検索オプションのコレクションです。 |

### 戻り値

見つかった署名のリストを含む [`SearchResult`](../../../groupdocs.signature.domain/searchresult) のインスタンスを返します。

### 備考

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 関連項目

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

提供された検索オプションを使用してドキュメント内の署名を検索し、指定された述語に基づいて結果をフィルタリングします。

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| searchOptionsList | List`1 | 署名検索の基準を定義する [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) インスタンスのリストです。 |
| predicate | Func`2 | 見つかった署名のリストに適用するフィルタ述語です。 |

### 戻り値

指定された検索オプションに一致し、述語を満たす署名を含む [`SearchResult`](../../../groupdocs.signature.domain/searchresult) を返します。

### 備考

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 関連項目

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

ドキュメント内の署名を [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) オプションで検索します。

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| searchOptions | SearchOptions | 検索オプションです。 |

### 戻り値

見つかった署名のリストを返します。

### 備考

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 関連項目

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

ドキュメント内の署名の正確なタイプを [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) の値で検索します。

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signatureType | SignatureType | 検索対象の署名タイプです。 |

### 戻り値

正確なタイプの見つかった署名のリストを返します。

### 備考

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 関連項目

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

ドキュメント内で指定された署名タイプを [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) の値で検索します。

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signatureTypes | SignatureType[] | 見つけるための1つまたは複数の署名タイプ。 |

### 戻り値

見つかった署名のリストを含む[`SearchResult`](../../../groupdocs.signature.domain/searchresult)のインスタンスを返します。

### 備考

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 関連項目

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

利用可能なすべての検索オプションを使用してドキュメント内の署名を検索し、指定された述語に基づいて結果をフィルタリングします。

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| predicate | Func`2 | 見つかった署名のリストに適用するフィルタ述語です。 |

### 戻り値

提供された述語を満たす[`BaseSignature`](../../../groupdocs.signature.domain/basesignature)インスタンスのリストを返します。

### 備考

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### 関連項目

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
