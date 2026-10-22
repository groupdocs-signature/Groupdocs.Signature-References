---
title: "Search"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Söker efter signaturer i ett dokument med SearchOptionsgroupdocs.signature.options/searchoptions-lista."
type: docs
weight: 150
url: /sv/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Söker efter signaturer i ett dokument med [`SearchOptions`](../../../groupdocs.signature.options/searchoptions)-lista.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchOptionsList | List`1 | Sökalternativsamlingen. |

### Returvärde

Returnerar en instans av [`SearchResult`](../../../groupdocs.signature.domain/searchresult) med en lista över hittade Signatures.

### Anmärkningar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Söker efter signaturer i dokumentet med de angivna sökalternativen och filtrerar resultaten baserat på det angivna predikatet.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchOptionsList | List`1 | En lista över [`SearchOptions`](../../../groupdocs.signature.options/searchoptions)-instanser som definierar kriterierna för att söka efter signaturer. |
| predikat | Func`2 | Filterpredikatet som ska tillämpas på listan med hittade signaturer. |

### Returvärde

Returnerar ett [`SearchResult`](../../../groupdocs.signature.domain/searchresult) som innehåller signaturerna som matchar de angivna sökalternativen och uppfyller predikatet.

### Anmärkningar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Söker efter signaturer i ett dokument med hjälp av [`SearchOptions`](../../../groupdocs.signature.options/searchoptions)-alternativ.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchOptions | SearchOptions | Sökalternativen. |

### Returvärde

Returnerar listan med hittade signaturer.

### Anmärkningar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Söker efter exakt typ av signaturer i dokumentet med hjälp av [`SignatureType`](../../../groupdocs.signature.domain/signaturetype)-värdet.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureType | SignatureType | Typen av signaturer att söka efter. |

### Returvärde

Returnerar listan med hittade signaturer med exakt typ.

### Anmärkningar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Söker efter angivna signaturtyper i dokumentet med hjälp av [`SignatureType`](../../../groupdocs.signature.domain/signaturetype)-värdet.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureTypes | SignatureType[] | En eller flera typer av signaturer att hitta. |

### Returvärde

Returnerar en instans av [`SearchResult`](../../../groupdocs.signature.domain/searchresult) med en lista över hittade signaturer.

### Anmärkningar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Söker efter signaturer i dokumentet med alla tillgängliga sökalternativ och filtrerar resultaten baserat på det angivna predikatet.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| predikat | Func`2 | Filterpredikatet som ska tillämpas på listan med hittade signaturer. |

### Returvärde

Returnerar en lista med [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)-instanser som uppfyller det angivna predikatet.

### Anmärkningar

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
