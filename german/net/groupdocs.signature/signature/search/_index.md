---
title: "Search"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Sucht nach Signaturen in einem Dokument anhand der SearchOptionsgroupdocs.signature.options/searchoptions-Liste."
type: docs
weight: 150
url: /de/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Sucht nach Signaturen in einem Dokument anhand der [`SearchOptions`](../../../groupdocs.signature.options/searchoptions)-Liste.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchOptionsList | List`1 | Die Sammlung der Suchoptionen. |

### Rückgabewert

Gibt eine Instanz von [`SearchResult`](../../../groupdocs.signature.domain/searchresult) mit einer Liste gefundener Signaturen zurück.

### Hinweise

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Durchsucht das Dokument nach Signaturen mit den bereitgestellten Suchoptionen und filtert die Ergebnisse anhand des angegebenen Prädikats.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchOptionsList | List`1 | Eine Liste von [`SearchOptions`](../../../groupdocs.signature.options/searchoptions)-Instanzen, die die Kriterien für die Suche nach Signaturen definieren. |
| Prädikat | Func`2 | Das Filter‑Prädikat, das auf die Liste gefundener Signaturen angewendet werden soll. |

### Rückgabewert

Gibt ein [`SearchResult`](../../../groupdocs.signature.domain/searchresult) zurück, das die Signaturen enthält, die den angegebenen Suchoptionen entsprechen und das Prädikat erfüllen.

### Hinweise

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Sucht nach Signaturen in einem Dokument anhand der [`SearchOptions`](../../../groupdocs.signature.options/searchoptions)-Optionen.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchOptions | SearchOptions | Die Suchoptionen. |

### Rückgabewert

Gibt die Liste gefundener Signaturen zurück.

### Hinweise

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Sucht nach dem genauen Signaturtyp im Dokument anhand des [`SignatureType`](../../../groupdocs.signature.domain/signaturetype)-Werts.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureType | SignatureType | Der Typ der zu suchenden Signaturen. |

### Rückgabewert

Gibt die Liste gefundener Signaturen mit exakt diesem Typ zurück.

### Hinweise

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Sucht nach angegebenen Signaturtypen im Dokument anhand des [`SignatureType`](../../../groupdocs.signature.domain/signaturetype)-Werts.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Ein oder mehrere Signaturtypen, die gefunden werden sollen. |

### Rückgabewert

Gibt eine Instanz von [`SearchResult`](../../../groupdocs.signature.domain/searchresult) mit einer Liste gefundener Signaturen zurück.

### Hinweise

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Durchsucht das Dokument nach Signaturen unter Verwendung aller verfügbaren Suchoptionen und filtert die Ergebnisse anhand des angegebenen Prädikats.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Prädikat | Func`2 | Das Filter‑Prädikat, das auf die Liste gefundener Signaturen angewendet werden soll. |

### Rückgabewert

Gibt eine Liste von [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)-Instanzen zurück, die das bereitgestellte Prädikat erfüllen.

### Hinweise

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
