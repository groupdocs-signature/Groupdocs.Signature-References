---
title: "Buscar"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Busca firmas en un documento mediante la lista de SearchOptionsgroupdocs.signature.options/searchoptions."
type: docs
weight: 150
url: /es/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Busca firmas en un documento mediante la lista de [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchOptionsList | List`1 | La colección de opciones de búsqueda. |

### Valor de retorno

Devuelve una instancia de [`SearchResult`](../../../groupdocs.signature.domain/searchresult) con la lista de firmas encontradas.

### Observaciones

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Busca firmas en el documento usando las opciones de búsqueda proporcionadas y filtra los resultados según el predicado especificado.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchOptionsList | List`1 | Una lista de instancias de [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) que definen los criterios para buscar firmas. |
| predicate | Func`2 | El predicado de filtro a aplicar sobre la lista de firmas encontradas. |

### Valor de retorno

Devuelve un [`SearchResult`](../../../groupdocs.signature.domain/searchresult) que contiene las firmas que coinciden con las opciones de búsqueda especificadas y satisfacen el predicado.

### Observaciones

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Busca firmas en un documento mediante las opciones de [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchOptions | SearchOptions | Las opciones de búsqueda. |

### Valor de retorno

Devuelve la lista de firmas encontradas.

### Observaciones

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Busca el tipo exacto de firmas en el documento mediante el valor de [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signatureType | SignatureType | El tipo de firmas a buscar. |

### Valor de retorno

Devuelve la lista de firmas encontradas con el tipo exacto.

### Observaciones

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Busca los tipos de firma especificados en el documento mediante el valor de [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Uno o varios tipos de firmas para encontrar. |

### Valor de retorno

Devuelve una instancia de [`SearchResult`](../../../groupdocs.signature.domain/searchresult) con la lista de firmas encontradas.

### Observaciones

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Busca firmas en el documento utilizando todas las opciones de búsqueda disponibles y filtra los resultados según el predicado especificado.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| predicate | Func`2 | El predicado de filtro a aplicar sobre la lista de firmas encontradas. |

### Valor de retorno

Devuelve una lista de instancias de [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) que cumplen el predicado proporcionado.

### Observaciones

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
