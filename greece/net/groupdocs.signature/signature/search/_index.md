---
title: Search
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Αναζητά υπογραφές σε ένα έγγραφο απόSearchOptionsgroupdocs.signature.options/searchoptions λίστα.
type: docs
weight: 150
url: /el/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Αναζητά υπογραφές σε ένα έγγραφο από[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) λίστα.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchOptionsList | List`1 | Η συλλογή επιλογών αναζήτησης. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SearchResult`](../../../groupdocs.signature.domain/searchresult) με λίστα με τις υπογραφές που βρέθηκαν.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με την αναζήτηση ηλεκτρονικών υπογραφών σε έγγραφα χρησιμοποιώντας GroupDocs.Υπογραφή: [Πώς να αναζητήσετε ηλεκτρονικές υπογραφές μέσα στο έγγραφο χρησιμοποιώντας C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Περισσότερα σχετικά με την αναζήτηση ηλεκτρονικών υπογραφών ανάλογα με τον τύπο eSign: [Περιπτώσεις προηγμένης χρήσης της αναζήτησης ηλεκτρονικών υπογραφών με το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Αναζητά υπογραφές σε ένα έγγραφο από[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) επιλογές.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| searchOptions | SearchOptions | Οι επιλογές αναζήτησης. |

### Επιστρεφόμενη Αξία

Επιστρέφει τη λίστα των υπογραφών που βρέθηκαν.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με την αναζήτηση ηλεκτρονικών υπογραφών σε έγγραφα χρησιμοποιώντας GroupDocs.Υπογραφή: [Πώς να αναζητήσετε ηλεκτρονικές υπογραφές μέσα στο έγγραφο χρησιμοποιώντας C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Περισσότερα σχετικά με την αναζήτηση ηλεκτρονικών υπογραφών ανάλογα με τον τύπο eSign: [Περιπτώσεις προηγμένης χρήσης της αναζήτησης ηλεκτρονικών υπογραφών με το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Αναζητά τον ακριβή τύπο υπογραφών στο έγγραφο από[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) τιμή.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureType | SignatureType | Ο τύπος των υπογραφών προς αναζήτηση. |

### Επιστρεφόμενη Αξία

Επιστρέφει τη λίστα των υπογραφών που βρέθηκαν με τον ακριβή τύπο.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με την αναζήτηση ηλεκτρονικών υπογραφών σε έγγραφα χρησιμοποιώντας GroupDocs.Υπογραφή: [Πώς να αναζητήσετε ηλεκτρονικές υπογραφές μέσα στο έγγραφο χρησιμοποιώντας C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Περισσότερα σχετικά με την αναζήτηση ηλεκτρονικών υπογραφών ανάλογα με τον τύπο eSign: [Περιπτώσεις προηγμένης χρήσης της αναζήτησης ηλεκτρονικών υπογραφών με το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Αναζητά συγκεκριμένους τύπους υπογραφών στο έγγραφο από[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) τιμή.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Ένας ή περισσότεροι τύποι υπογραφών για εύρεση. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SearchResult`](../../../groupdocs.signature.domain/searchresult) με λίστα υπογραφών που βρέθηκαν.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με την αναζήτηση ηλεκτρονικών υπογραφών σε έγγραφα χρησιμοποιώντας GroupDocs.Υπογραφή: [Πώς να αναζητήσετε ηλεκτρονικές υπογραφές μέσα στο έγγραφο χρησιμοποιώντας C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Περισσότερα σχετικά με την αναζήτηση ηλεκτρονικών υπογραφών ανάλογα με τον τύπο eSign: [Περιπτώσεις προηγμένης χρήσης της αναζήτησης ηλεκτρονικών υπογραφών με το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Δείτε επίσης

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
