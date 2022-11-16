---
title: Search
second_title: GroupDocs.Signature för .NET API-referens
description: Söker efter signaturer i ett dokument avSearchOptionsgroupdocs.signature.options/searchoptions list.
type: docs
weight: 150
url: /sv/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Söker efter signaturer i ett dokument av[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) list.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchOptionsList | List`1 | Samlingen av sökalternativ. |

### Returvärde

Returnerar instans av[`SearchResult`](../../../groupdocs.signature.domain/searchresult) med lista över hittade signaturer.

### Anmärkningar

**Läs mer**

* Mer om att söka elektroniska signaturer i ett dokument med hjälp av GroupDocs.Signatur: [Hur man söker efter elektroniska signaturer i dokument med C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Mer om elektroniska signatursökningar beroende på eSign-typ: [Avancerad användning av elektroniska signatursökningar med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Söker efter signaturer i ett dokument av[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) alternativ.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchOptions | SearchOptions | Sökalternativen. |

### Returvärde

Returnerar listan över hittade signaturer.

### Anmärkningar

**Läs mer**

* Mer om att söka elektroniska signaturer i ett dokument med hjälp av GroupDocs.Signatur: [Hur man söker efter elektroniska signaturer i dokument med C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Mer om elektroniska signatursökningar beroende på eSign-typ: [Avancerad användning av elektroniska signatursökningar med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Söker efter exakt typ av signaturer i dokumentet med[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) värde.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureType | SignatureType | Typen av signaturer att söka efter. |

### Returvärde

Returnerar listan över hittade signaturer med exakt typ.

### Anmärkningar

**Läs mer**

* Mer om att söka elektroniska signaturer i ett dokument med hjälp av GroupDocs.Signatur: [Hur man söker efter elektroniska signaturer i dokument med C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Mer om elektroniska signatursökningar beroende på eSign-typ: [Avancerad användning av elektroniska signatursökningar med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Söker efter specificerade signaturtyper i dokumentet med[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) värde.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureTypes | SignatureType[] | En eller flera typer av signaturer att hitta. |

### Returvärde

Returnerar instans av[`SearchResult`](../../../groupdocs.signature.domain/searchresult) med lista över hittade signaturer.

### Anmärkningar

**Läs mer**

* Mer om att söka elektroniska signaturer i ett dokument med hjälp av GroupDocs.Signatur: [Hur man söker efter elektroniska signaturer i dokument med C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Mer om elektroniska signatursökningar beroende på eSign-typ: [Avancerad användning av elektroniska signatursökningar med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Se även

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
