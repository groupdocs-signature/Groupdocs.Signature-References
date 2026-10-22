---
title: "Ara"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Belgedeki imzaları SearchOptionsgroupdocs.signature.options/searchoptions listesiyle arar."
type: docs
weight: 150
url: /tr/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Belgedeki imzaları [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) listesiyle arar.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchOptionsList | List`1 | Arama seçenekleri koleksiyonu. |

### Dönüş Değeri

Bulunan İmzaların listesiyle [`SearchResult`](../../../groupdocs.signature.domain/searchresult) örneğini döndürür.

### Açıklamalar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca Bakınız

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Belgedeki imzaları, sağlanan arama seçeneklerini kullanarak arar ve sonuçları belirtilen koşula göre filtreler.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchOptionsList | List`1 | İmzaları arama kriterlerini tanımlayan [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) örneklerinin bir listesi. |
| predicate | Func`2 | Bulunan imzaların listesine uygulanacak filtre koşulu. |

### Dönüş Değeri

Belirtilen arama seçenekleriyle eşleşen ve koşulu sağlayan imzaları içeren bir [`SearchResult`](../../../groupdocs.signature.domain/searchresult) döndürür.

### Açıklamalar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca Bakınız

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Belgedeki imzaları [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) seçenekleriyle arar.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchOptions | SearchOptions | Arama seçenekleri. |

### Dönüş Değeri

Bulunan imzaların listesini döndürür.

### Açıklamalar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca Bakınız

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Belgedeki imzaların kesin türünü [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) değeriyle arar.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureType | SignatureType | Aranacak imzaların türü. |

### Dönüş Değeri

Kesin türde bulunan imzaların listesini döndürür.

### Açıklamalar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca Bakınız

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Belgedeki belirtilen imza türlerini [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) değeriyle arar.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Bulmak için bir veya birkaç imza türü. |

### Dönüş Değeri

Bulunan imzaların listesiyle birlikte [`SearchResult`](../../../groupdocs.signature.domain/searchresult) örneğini döndürür.

### Açıklamalar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca Bakınız

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Belgedeki imzaları mevcut tüm arama seçeneklerini kullanarak arar ve belirtilen koşula göre sonuçları filtreler.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| predicate | Func`2 | Bulunan imzaların listesine uygulanacak filtre koşulu. |

### Dönüş Değeri

Sağlanan koşulu sağlayan [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) örneklerinin bir listesini döndürür.

### Açıklamalar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca Bakınız

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
