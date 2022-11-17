---
title: Search
second_title: Riferimento API GroupDocs.Signature per .NET
description: Cerca le firme in un documento perSearchOptionsgroupdocs.signature.options/searchoptions elenco.
type: docs
weight: 150
url: /it/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Cerca le firme in un documento per[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) elenco.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| searchOptionsList | List`1 | La raccolta delle opzioni di ricerca. |

### Valore di ritorno

Restituisce l'istanza di[`SearchResult`](../../../groupdocs.signature.domain/searchresult) con l'elenco delle firme trovate.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sulla ricerca di firme elettroniche in un documento utilizzando GroupDocs.Signature: [Come cercare firme elettroniche all'interno di un documento usando C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Ulteriori informazioni sulla ricerca di firme elettroniche in base al tipo di firma elettronica: [Casi d'uso avanzati di ricerca di firme elettroniche con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Guarda anche

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Cerca le firme in un documento per[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) opzioni.

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

**Scopri di più**

* Ulteriori informazioni sulla ricerca di firme elettroniche in un documento utilizzando GroupDocs.Signature: [Come cercare firme elettroniche all'interno di un documento usando C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Ulteriori informazioni sulla ricerca di firme elettroniche in base al tipo di firma elettronica: [Casi d'uso avanzati di ricerca di firme elettroniche con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Guarda anche

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Cerca il tipo esatto di firme nel documento per[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) valore.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureType | SignatureType | Il tipo di firme da cercare. |

### Valore di ritorno

Restituisce l'elenco delle firme trovate con il tipo esatto.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sulla ricerca di firme elettroniche in un documento utilizzando GroupDocs.Signature: [Come cercare firme elettroniche all'interno di un documento usando C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Ulteriori informazioni sulla ricerca di firme elettroniche in base al tipo di firma elettronica: [Casi d'uso avanzati di ricerca di firme elettroniche con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Guarda anche

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Cerca i tipi di firma specificati nel documento per[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) valore.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Uno o più tipi di firme da trovare. |

### Valore di ritorno

Restituisce l'istanza di[`SearchResult`](../../../groupdocs.signature.domain/searchresult) con elenco delle firme trovate.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sulla ricerca di firme elettroniche in un documento utilizzando GroupDocs.Signature: [Come cercare firme elettroniche all'interno di un documento usando C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Ulteriori informazioni sulla ricerca di firme elettroniche in base al tipo di firma elettronica: [Casi d'uso avanzati di ricerca di firme elettroniche con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Guarda anche

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
