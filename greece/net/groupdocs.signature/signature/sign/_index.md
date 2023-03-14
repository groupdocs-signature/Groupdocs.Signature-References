---
title: Sign
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Υπογράφει έγγραφο μεSignOptionsgroupdocs.signature.options/signoptions και αποθηκεύει το αποτέλεσμα σε μια ροή.
type: docs
weight: 160
url: /el/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Υπογράφει έγγραφο με[`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή εγγράφου εξόδου. |
| signOptions | SignOptions | Οι επιλογές υπογραφής. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα υπογραφών που δημιουργήθηκαν πρόσφατα.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Υπογραφή: [Τύποι ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Περισσότερα για τον τρόπο με τον οποίο το eSign εγγράφει σε C#: [Τρόπος ηλεκτρονικής υπογραφής εγγράφων χρησιμοποιώντας GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Υπογράφει έγγραφο με[`SignOptions`](../../../groupdocs.signature.options/signoptions)και αποθηκεύει το αποτέλεσμα σε μια ροή με προκαθορισμένα[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή εγγράφου εξόδου. |
| signOptions | SignOptions | Οι επιλογές υπογραφής. |
| saveOptions | SaveOptions | Οι επιλογές αποθήκευσης. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα υπογραφών που δημιουργήθηκαν πρόσφατα.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Υπογραφή: [Τύποι ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Περισσότερα για τον τρόπο με τον οποίο το eSign εγγράφει σε C#: [Τρόπος ηλεκτρονικής υπογραφής εγγράφων χρησιμοποιώντας GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Περισσότερα σχετικά με τον τρόπο αποθήκευσης ηλεκτρονικά υπογεγραμμένων εγγράφων και προσαρμογής της διαδικασίας αποθήκευσης: [Πώς να προσαρμόσετε ηλεκτρονικά υπογεγραμμένα έγγραφα κατά την αποθήκευση χρησιμοποιώντας το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Υπογράφει έγγραφο με συλλογή από[`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή εγγράφου εξόδου. |
| signOptionsList | List`1 | Η λίστα των επιλογών υπογραφής. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα υπογραφών που δημιουργήθηκαν πρόσφατα.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Υπογραφή: [Τύποι ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Περισσότερα για τον τρόπο με τον οποίο το eSign εγγράφει σε C#: [Τρόπος ηλεκτρονικής υπογραφής εγγράφων χρησιμοποιώντας GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Υπογράφει έγγραφο με συλλογή από[`SignOptions`](../../../groupdocs.signature.options/signoptions)και αποθηκεύει το αποτέλεσμα σε μια ροή με προκαθορισμένα[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή εγγράφου εξόδου. |
| signOptionsList | List`1 | Η λίστα των επιλογών υπογραφής. |
| saveOptions | SaveOptions | Οι επιλογές αποθήκευσης. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα υπογραφών που δημιουργήθηκαν πρόσφατα.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Υπογραφή: [Τύποι ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Περισσότερα για τον τρόπο με τον οποίο το eSign εγγράφει σε C#: [Τρόπος ηλεκτρονικής υπογραφής εγγράφων χρησιμοποιώντας GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Περισσότερα σχετικά με τον τρόπο αποθήκευσης ηλεκτρονικά υπογεγραμμένων εγγράφων και προσαρμογής της διαδικασίας αποθήκευσης: [Πώς να προσαρμόσετε ηλεκτρονικά υπογεγραμμένα έγγραφα κατά την αποθήκευση χρησιμοποιώντας το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Υπογράφει έγγραφο με[`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε καθορισμένη διαδρομή αρχείου.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου εξόδου. |
| signOptions | SignOptions | Οι επιλογές υπογραφής. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα υπογραφών που δημιουργήθηκαν πρόσφατα.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Υπογραφή: [Τύποι ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Περισσότερα για τον τρόπο με τον οποίο το eSign εγγράφει σε C#: [Τρόπος ηλεκτρονικής υπογραφής εγγράφων χρησιμοποιώντας GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Υπογράφει έγγραφο με[`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε καθορισμένη διαδρομή αρχείου με προκαθορισμένη[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου εξόδου. |
| signOptions | SignOptions | Οι επιλογές υπογραφής. |
| saveOptions | SaveOptions | Οι επιλογές αποθήκευσης. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα υπογραφών που δημιουργήθηκαν πρόσφατα.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Υπογραφή: [Τύποι ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Περισσότερα για τον τρόπο με τον οποίο το eSign εγγράφει σε C#: [Τρόπος ηλεκτρονικής υπογραφής εγγράφων χρησιμοποιώντας GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Περισσότερα σχετικά με τον τρόπο αποθήκευσης ηλεκτρονικά υπογεγραμμένων εγγράφων και προσαρμογής της διαδικασίας αποθήκευσης: [Πώς να προσαρμόσετε ηλεκτρονικά υπογεγραμμένα έγγραφα κατά την αποθήκευση χρησιμοποιώντας το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Υπογράφει έγγραφο με συλλογή από[`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε καθορισμένη διαδρομή αρχείου.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου εξόδου. |
| signOptionsList | List`1 | Η λίστα των επιλογών υπογραφής. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα υπογραφών που δημιουργήθηκαν πρόσφατα.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Υπογραφή: [Τύποι ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Περισσότερα για τον τρόπο με τον οποίο το eSign εγγράφει σε C#: [Τρόπος ηλεκτρονικής υπογραφής εγγράφων χρησιμοποιώντας GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Υπογράφει έγγραφο με συλλογή από[`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε καθορισμένη διαδρομή αρχείου με προκαθορισμένη[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου εξόδου. |
| signOptionsList | List`1 | Η λίστα των επιλογών υπογραφής. |
| saveOptions | SaveOptions | Οι επιλογές αποθήκευσης. |

### Επιστρεφόμενη Αξία

Επιστρέφει το παράδειγμα του[`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα υπογραφών που δημιουργήθηκαν πρόσφατα.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Υπογραφή: [Τύποι ηλεκτρονικών υπογραφών που υποστηρίζονται από το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Περισσότερα για τον τρόπο με τον οποίο το eSign εγγράφει σε C#: [Τρόπος ηλεκτρονικής υπογραφής εγγράφων χρησιμοποιώντας GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Περισσότερα σχετικά με τον τρόπο αποθήκευσης ηλεκτρονικά υπογεγραμμένων εγγράφων και προσαρμογής της διαδικασίας αποθήκευσης: [Πώς να προσαρμόσετε ηλεκτρονικά υπογεγραμμένα έγγραφα κατά την αποθήκευση χρησιμοποιώντας το GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
