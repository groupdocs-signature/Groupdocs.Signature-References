---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιγράφει την εμφάνιση της Γραμμής Υπογραφής για Ψηφιακή Υπογραφή."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Περιγράφει την εμφάνιση της Γραμμής Υπογραφής για Ψηφιακή Υπογραφή. Μία Γραμμή Υπογραφής μπορεί να εφαρμοστεί μόνο για μία Ψηφιακή Υπογραφή. Η Γραμμή Υπογραφής βρίσκεται πάντα στην πρώτη σελίδα. Αυτή η δυνατότητα μπορεί να είναι χρήσιμη για μορφές αρχείων .docx, .doc, .odt και .xlsx.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Δημιουργεί αντικείμενο εμφάνισης Γραμμής Υπογραφής. |
| [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί την εμφάνιση Γραμμής Υπογραφής με τις καθορισμένες τιμές (signer, title, email). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSigner()](#getSigner--) | Λαμβάνει ή ορίζει το όνομα του υπογράφοντα για τη γραμμή υπογραφής. |
| [setSigner(String value)](#setSigner-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του υπογράφοντα για τη γραμμή υπογραφής. |
| [getTitle()](#getTitle--) | Λαμβάνει ή ορίζει έναν τίτλο για τη γραμμή υπογραφής. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Λαμβάνει ή ορίζει έναν τίτλο για τη γραμμή υπογραφής. |
| [getEmail()](#getEmail--) | Λαμβάνει ή ορίζει ένα email που θα εμφανίζεται στη γραμμή υπογραφής. |
| [setEmail(String value)](#setEmail-java.lang.String-) | Λαμβάνει ή ορίζει ένα email που θα εμφανίζεται στη γραμμή υπογραφής. |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά. |
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Δημιουργεί αντικείμενο εμφάνισης Γραμμής Υπογραφής.

### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Δημιουργεί την εμφάνιση Γραμμής Υπογραφής με τις καθορισμένες τιμές (signer, title, email).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| υπογράφων | java.lang.String | Όνομα υπογράφοντα. |
| τίτλος | java.lang.String | Τίτλος υπογραφής. |
| email | java.lang.String | Ηλεκτρονική διεύθυνση του συγγραφέα. |

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Λαμβάνει ή ορίζει το όνομα του υπογράφοντα για τη γραμμή υπογραφής.

**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Λαμβάνει ή ορίζει το όνομα του υπογράφοντα για τη γραμμή υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Λαμβάνει ή ορίζει έναν τίτλο για τη γραμμή υπογραφής.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Λαμβάνει ή ορίζει έναν τίτλο για τη γραμμή υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Λαμβάνει ή ορίζει ένα email που θα εμφανίζεται στη γραμμή υπογραφής.

**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Λαμβάνει ή ορίζει ένα email που θα εμφανίζεται στη γραμμή υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Παρακάμπτει τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
