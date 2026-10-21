---
title: "Cerca"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Cerca firme in un documento tramite l'elenco SearchOptionsgroupdocs.signature.options/searchoptions."
type: docs
weight: 150
url: /it/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Cerca firme in un documento tramite l'elenco [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchOptionsList | List`1 | La collezione delle opzioni di ricerca. |

### Valore di ritorno

Restituisce un'istanza di [`SearchResult`](../../../groupdocs.signature.domain/searchresult) con l'elenco delle firme trovate.

### Osservazioni

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Vedi anche

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Cerca firme nel documento utilizzando le opzioni di ricerca fornite e filtra i risultati in base al predicato specificato.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchOptionsList | List`1 | Un elenco di istanze di [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) che definiscono i criteri per la ricerca delle firme. |
| predicate | Func`2 | Il predicato di filtro da applicare all'elenco delle firme trovate. |

### Valore di ritorno

Restituisce un [`SearchResult`](../../../groupdocs.signature.domain/searchresult) contenente le firme che corrispondono alle opzioni di ricerca specificate e soddisfano il predicato.

### Osservazioni

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Vedi anche

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Cerca firme in un documento tramite le opzioni [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchOptions | SearchOptions | Le opzioni di ricerca. |

### Valore di ritorno

Restituisce l'elenco delle firme trovate.

### Osservazioni

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Vedi anche

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Cerca il tipo esatto di firme nel documento tramite il valore [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureType | SignatureType | Il tipo di firme da cercare. |

### Valore di ritorno

Restituisce l'elenco delle firme trovate con tipo esatto.

### Osservazioni

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Vedi anche

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Cerca i tipi di firme specificati nel documento tramite il valore [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Uno o più tipi di firme da trovare. |

### Valore di ritorno

Restituisce un'istanza di [`SearchResult`](../../../groupdocs.signature.domain/searchresult) con l'elenco delle firme trovate.

### Osservazioni

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Vedi anche

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Cerca le firme nel documento utilizzando tutte le opzioni di ricerca disponibili e filtra i risultati in base al predicato specificato.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| predicate | Func`2 | Il predicato di filtro da applicare all'elenco delle firme trovate. |

### Valore di ritorno

Restituisce un elenco di istanze di [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) che soddisfano il predicato fornito.

### Osservazioni

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Vedi anche

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
