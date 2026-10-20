---
title: "Search"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Αναζητά υπογραφές σε ένα έγγραφο με τη λίστα SearchOptionsgroupdocs.signature.options/searchoptions."
type: docs
weight: 150
url: /el/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Αναζητά υπογραφές σε ένα έγγραφο με τη λίστα [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchOptionsList | List`1 | Η συλλογή των επιλογών αναζήτησης. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SearchResult`](../../../groupdocs.signature.domain/searchresult) με λίστα των ευρεθέντων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Αναζητά υπογραφές στο έγγραφο χρησιμοποιώντας τις παρεχόμενες επιλογές αναζήτησης και φιλτράρει τα αποτελέσματα βάσει της καθορισμένης συνθήκης.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchOptionsList | List`1 | Μια λίστα από στιγμιότυπα του [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) που ορίζουν τα κριτήρια για την αναζήτηση υπογραφών. |
| predicate | Func`2 | Η συνάρτηση predicate που θα εφαρμοστεί στη λίστα των ευρεθέντων υπογραφών. |

### Τιμή Επιστροφής

Επιστρέφει ένα [`SearchResult`](../../../groupdocs.signature.domain/searchresult) που περιέχει τις υπογραφές που ταιριάζουν με τις καθορισμένες επιλογές αναζήτησης και ικανοποιούν το predicate.

### Παρατηρήσεις

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Αναζητά υπογραφές σε ένα έγγραφο με τις επιλογές [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchOptions | SearchOptions | Οι επιλογές αναζήτησης. |

### Τιμή Επιστροφής

Επιστρέφει τη λίστα των ευρεθέντων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Αναζητά ακριβή τύπο υπογραφών στο έγγραφο με την τιμή του [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureType | SignatureType | Ο τύπος των υπογραφών προς αναζήτηση. |

### Τιμή Επιστροφής

Επιστρέφει τη λίστα των ευρεθέντων υπογραφών με ακριβή τύπο.

### Παρατηρήσεις

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Αναζητά καθορισμένους τύπους υπογραφών στο έγγραφο με την τιμή του [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Ένας ή πολλοί τύποι υπογραφών για εύρεση. |

### Τιμή Επιστροφής

Επιστρέφει ένα αντικείμενο του [`SearchResult`](../../../groupdocs.signature.domain/searchresult) με λίστα των βρεθεισών υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Αναζητά υπογραφές στο έγγραφο χρησιμοποιώντας όλες τις διαθέσιμες επιλογές αναζήτησης και φιλτράρει τα αποτελέσματα βάσει του καθορισμένου προδιαγραφέα.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| predicate | Func`2 | Η συνάρτηση predicate που θα εφαρμοστεί στη λίστα των ευρεθέντων υπογραφών. |

### Τιμή Επιστροφής

Επιστρέφει μια λίστα από αντικείμενα του [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) που ικανοποιούν την παρεχόμενη προδιαγραφή.

### Παρατηρήσεις

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
