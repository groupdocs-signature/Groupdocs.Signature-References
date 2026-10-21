---
title: "Zoeken"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Zoekt naar handtekeningen in een document op basis van de lijst met SearchOptionsgroupdocs.signature.options/searchoptions."
type: docs
weight: 150
url: /nl/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Zoekt naar handtekeningen in een document op basis van de lijst met [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) lijst.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchOptionsList | List`1 | De collectie zoekopties. |

### Retourwaarde

Retourneert een instantie van [`SearchResult`](../../../groupdocs.signature.domain/searchresult) met een lijst van gevonden handtekeningen.

### Opmerkingen

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Zoekt handtekeningen in het document met behulp van de opgegeven zoekopties en filtert de resultaten op basis van het opgegeven predicaat.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchOptionsList | List`1 | Een lijst van [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) instanties die de criteria definiëren voor het zoeken naar handtekeningen. |
| predicate | Func`2 | Het filterpredicaat dat moet worden toegepast op de lijst met gevonden handtekeningen. |

### Retourwaarde

Retourneert een [`SearchResult`](../../../groupdocs.signature.domain/searchresult) dat de handtekeningen bevat die overeenkomen met de opgegeven zoekopties en voldoen aan het predicaat.

### Opmerkingen

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Zoekt naar handtekeningen in een document op basis van [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) opties.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchOptions | SearchOptions | De zoekopties. |

### Retourwaarde

Retourneert de lijst met gevonden handtekeningen.

### Opmerkingen

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Zoekt naar het exacte type handtekeningen in het document op basis van de waarde van [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureType | SignatureType | Het type handtekeningen om te zoeken. |

### Retourwaarde

Retourneert de lijst met gevonden handtekeningen met exact type.

### Opmerkingen

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Zoekt naar opgegeven handtekeningtypen in het document op basis van de waarde van [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Een of meerdere typen handtekeningen om te vinden. |

### Retourwaarde

Retourneert een instantie van [`SearchResult`](../../../groupdocs.signature.domain/searchresult) met een lijst van gevonden handtekeningen.

### Opmerkingen

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Zoekt naar handtekeningen in het document met alle beschikbare zoekopties en filtert de resultaten op basis van het opgegeven predicaat.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| predicate | Func`2 | Het filterpredicaat dat moet worden toegepast op de lijst met gevonden handtekeningen. |

### Retourwaarde

Retourneert een lijst van [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) instanties die voldoen aan het opgegeven predicaat.

### Opmerkingen

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
