---
title: Search
second_title: GroupDocs.Signature voor .NET API-referentie
description: Zoekt naar handtekeningen in een document opSearchOptionsgroupdocs.signature.options/searchoptions lijst.
type: docs
weight: 150
url: /nl/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Zoekt naar handtekeningen in een document op[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) lijst.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchOptionsList | List`1 | De verzameling zoekopties. |

### Winstwaarde

Retourneert instantie van[`SearchResult`](../../../groupdocs.signature.domain/searchresult) met lijst van gevonden handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over zoeken naar elektronische handtekeningen in documenten met GroupDocs.Signature: [Hoe te zoeken naar elektronische handtekeningen in een document met behulp van C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Meer over zoeken naar elektronische handtekeningen afhankelijk van type eSign: [Geavanceerd gebruik van zoeken naar elektronische handtekeningen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Zoekt naar handtekeningen in een document op[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) opties.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchOptions | SearchOptions | De zoekmogelijkheden. |

### Winstwaarde

Retourneert de lijst met gevonden handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over zoeken naar elektronische handtekeningen in documenten met GroupDocs.Signature: [Hoe te zoeken naar elektronische handtekeningen in een document met behulp van C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Meer over zoeken naar elektronische handtekeningen afhankelijk van type eSign: [Geavanceerd gebruik van zoeken naar elektronische handtekeningen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Zoekt naar het exacte type handtekeningen in het document door[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) waarde.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureType | SignatureType | Het type handtekeningen om te zoeken. |

### Winstwaarde

Retourneert de lijst met gevonden handtekeningen met het exacte type.

### Opmerkingen

**Kom meer te weten**

* Meer over zoeken naar elektronische handtekeningen in documenten met GroupDocs.Signature: [Hoe te zoeken naar elektronische handtekeningen in een document met behulp van C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Meer over zoeken naar elektronische handtekeningen afhankelijk van type eSign: [Geavanceerd gebruik van zoeken naar elektronische handtekeningen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Zoekt naar gespecificeerde handtekeningtypes in het document op[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) waarde.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Een of meerdere soorten handtekeningen om te vinden. |

### Winstwaarde

Retourneert instantie van[`SearchResult`](../../../groupdocs.signature.domain/searchresult) met lijst van gevonden handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over zoeken naar elektronische handtekeningen in documenten met GroupDocs.Signature: [Hoe te zoeken naar elektronische handtekeningen in een document met behulp van C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Meer over zoeken naar elektronische handtekeningen afhankelijk van type eSign: [Geavanceerd gebruik van zoeken naar elektronische handtekeningen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Zie ook

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
