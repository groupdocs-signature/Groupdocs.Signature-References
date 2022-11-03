---
title: Search
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Sucht nach Unterschriften in einem Dokument vonSearchOptionsgroupdocs.signature.options/searchoptions Liste.
type: docs
weight: 150
url: /de/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Sucht nach Unterschriften in einem Dokument von[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) Liste.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchOptionsList | List`1 | Die Sammlung der Suchoptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SearchResult`](../../../groupdocs.signature.domain/searchresult) mit Liste der gefundenen Signaturen.

### Bemerkungen

**Mehr erfahren**

* Mehr über die Suche nach elektronischen Signaturen in Dokumenten mit GroupDocs.Signature: [So suchen Sie mit C# nach elektronischen Signaturen im Dokument](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Mehr zur Suche nach elektronischen Signaturen abhängig vom eSign-Typ: [Erweiterte Anwendungsfälle der Suche nach elektronischen Signaturen mit GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Sucht nach Unterschriften in einem Dokument von[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) Optionen.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| searchOptions | SearchOptions | Die Suchoptionen. |

### Rückgabewert

Gibt die Liste der gefundenen Signaturen zurück.

### Bemerkungen

**Mehr erfahren**

* Mehr über die Suche nach elektronischen Signaturen in Dokumenten mit GroupDocs.Signature: [So suchen Sie mit C# nach elektronischen Signaturen im Dokument](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Mehr zur Suche nach elektronischen Signaturen abhängig vom eSign-Typ: [Erweiterte Anwendungsfälle der Suche nach elektronischen Signaturen mit GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Sucht nach dem genauen Signaturtyp im Dokument von[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) wert.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureType | SignatureType | Der Typ der zu durchsuchenden Signaturen. |

### Rückgabewert

Gibt die Liste der gefundenen Signaturen mit exaktem Typ zurück.

### Bemerkungen

**Mehr erfahren**

* Mehr über die Suche nach elektronischen Signaturen in Dokumenten mit GroupDocs.Signature: [So suchen Sie mit C# nach elektronischen Signaturen im Dokument](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Mehr zur Suche nach elektronischen Signaturen abhängig vom eSign-Typ: [Erweiterte Anwendungsfälle der Suche nach elektronischen Signaturen mit GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Sucht nach bestimmten Signaturtypen im Dokument nach[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) wert.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Eine oder mehrere Arten von Signaturen, die gesucht werden sollen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SearchResult`](../../../groupdocs.signature.domain/searchresult) mit Liste der gefundenen Signaturen.

### Bemerkungen

**Mehr erfahren**

* Mehr über die Suche nach elektronischen Signaturen in Dokumenten mit GroupDocs.Signature: [So suchen Sie mit C# nach elektronischen Signaturen im Dokument](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Mehr zur Suche nach elektronischen Signaturen abhängig vom eSign-Typ: [Erweiterte Anwendungsfälle der Suche nach elektronischen Signaturen mit GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Siehe auch

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
