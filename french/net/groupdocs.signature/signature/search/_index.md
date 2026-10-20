---
title: "Recherche"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Recherche des signatures dans un document par la liste SearchOptionsgroupdocs.signature.options/searchoptions."
type: docs
weight: 150
url: /fr/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Recherche des signatures dans un document par la liste [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| searchOptionsList | List`1 | La collection d'options de recherche. |

### Valeur de retour

Renvoie une instance de [`SearchResult`](../../../groupdocs.signature.domain/searchresult) avec la liste des signatures trouvées.

### Remarques

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir aussi

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Recherche les signatures dans le document en utilisant les options de recherche fournies et filtre les résultats selon le prédicat spécifié.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| searchOptionsList | List`1 | Une liste d'instances de [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) définissant les critères de recherche des signatures. |
| predicate | Func`2 | Le prédicat de filtrage à appliquer sur la liste des signatures trouvées. |

### Valeur de retour

Renvoie un [`SearchResult`](../../../groupdocs.signature.domain/searchresult) contenant les signatures qui correspondent aux options de recherche spécifiées et qui satisfont le prédicat.

### Remarques

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir aussi

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Recherche des signatures dans un document par les options [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Paramètre | Type | Description |
| --- | --- | --- |
| searchOptions | SearchOptions | Les options de recherche. |

### Valeur de retour

Renvoie la liste des signatures trouvées.

### Remarques

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir aussi

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Recherche le type exact de signatures dans le document par la valeur [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signatureType | SignatureType | Le type de signatures à rechercher. |

### Valeur de retour

Renvoie la liste des signatures trouvées avec le type exact.

### Remarques

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir aussi

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Recherche les types de signatures spécifiés dans le document par la valeur [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Un ou plusieurs types de signatures à rechercher. |

### Valeur de retour

Renvoie une instance de [`SearchResult`](../../../groupdocs.signature.domain/searchresult) avec la liste des signatures trouvées.

### Remarques

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir aussi

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Recherche des signatures dans le document en utilisant toutes les options de recherche disponibles et filtre les résultats selon le prédicat spécifié.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| predicate | Func`2 | Le prédicat de filtrage à appliquer sur la liste des signatures trouvées. |

### Valeur de retour

Renvoie une liste d'instances de [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) qui satisfont le prédicat fourni.

### Remarques

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir aussi

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
