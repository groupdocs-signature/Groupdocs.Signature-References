---
title: "Search"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Ищет подписи в документе по списку SearchOptionsgroupdocs.signature.options/searchoptions."
type: docs
weight: 150
url: /ru/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Ищет подписи в документе по списку [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchOptionsList | List`1 | Коллекция параметров поиска. |

### Возвращаемое значение

Возвращает экземпляр [`SearchResult`](../../../groupdocs.signature.domain/searchresult) со списком найденных подписей.

### Примечания

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### См. также

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Ищет подписи в документе, используя предоставленные параметры поиска, и фильтрует результаты на основе указанного предиката.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchOptionsList | List`1 | Список экземпляров [`SearchOptions`](../../../groupdocs.signature.options/searchoptions), определяющих критерии поиска подписей. |
| predicate | Func`2 | Фильтрующий предикат, применяемый к списку найденных подписей. |

### Возвращаемое значение

Возвращает [`SearchResult`](../../../groupdocs.signature.domain/searchresult), содержащий подписи, соответствующие указанным параметрам поиска и удовлетворяющие предикату.

### Примечания

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### См. также

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Ищет подписи в документе по параметрам [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchOptions | SearchOptions | Параметры поиска. |

### Возвращаемое значение

Возвращает список найденных подписей.

### Примечания

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### См. также

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Ищет подписи точного типа в документе по значению [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureType | SignatureType | Тип подписей для поиска. |

### Возвращаемое значение

Возвращает список найденных подписей точного типа.

### Примечания

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### См. также

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Ищет указанные типы подписей в документе по значению [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Один или несколько типов подписей для поиска. |

### Возвращаемое значение

Возвращает экземпляр [`SearchResult`](../../../groupdocs.signature.domain/searchresult) со списком найденных подписей.

### Примечания

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### См. также

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Ищет подписи в документе, используя все доступные параметры поиска, и фильтрует результаты на основе указанного предиката.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| predicate | Func`2 | Фильтрующий предикат, применяемый к списку найденных подписей. |

### Возвращаемое значение

Возвращает список экземпляров [`BaseSignature`](../../../groupdocs.signature.domain/basesignature), удовлетворяющих заданному предикату.

### Примечания

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### См. также

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
