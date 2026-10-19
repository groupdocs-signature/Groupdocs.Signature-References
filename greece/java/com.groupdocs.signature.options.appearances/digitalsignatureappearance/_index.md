---
title: "DigitalSignatureAppearance"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιγράφει την εμφάνιση της Γραμμής Υπογραφής για Ψηφιακή Υπογραφή."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Περιγράφει την εμφάνιση της Γραμμής Υπογραφής για Ψηφιακή Υπογραφή.
Μία Signature Line μπορεί να εφαρμοστεί μόνο για μία Digital Signature.
Η Signature Line βρίσκεται πάντα στην πρώτη σελίδα.
Αυτή η δυνατότητα μπορεί να είναι χρήσιμη για τις μορφές αρχείων .docx, .doc, .odt και .xlsx.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Δημιουργεί το αντικείμενο Signature Line Appearance. |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί Signature Line Appearance με τις καθορισμένες τιμές (signer, title, email). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSigner()](#getSigner--) | Λαμβάνει ή ορίζει το όνομα του signer για τη signature line. |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του signer για τη signature line. |
|
|  | [getTitle()](#getTitle--) | Λαμβάνει ή ορίζει έναν τίτλο για τη signature line. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Λαμβάνει ή ορίζει έναν τίτλο για τη signature line. |
|
|  | [getEmail()](#getEmail--) | Λαμβάνει ή ορίζει ένα email που θα εμφανίζεται στη signature line. |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | Λαμβάνει ή ορίζει ένα email που θα εμφανίζεται στη signature line. |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Δημιουργεί το αντικείμενο Signature Line Appearance.


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Δημιουργεί Signature Line Appearance με τις καθορισμένες τιμές (signer, title, email).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | υπογράφων | java.lang.String | Όνομα υπογράφοντα. |
|
|  | τίτλος | java.lang.String | Τίτλος υπογραφής. |
|
|  | ηλεκτρονική διεύθυνση | java.lang.String | Η διεύθυνση email του Συγγραφέα. |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Λαμβάνει ή ορίζει το όνομα του signer για τη signature line.


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Λαμβάνει ή ορίζει το όνομα του signer για τη signature line.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Λαμβάνει ή ορίζει έναν τίτλο για τη signature line.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Λαμβάνει ή ορίζει έναν τίτλο για τη signature line.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Λαμβάνει ή ορίζει ένα email που θα εμφανίζεται στη signature line.


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Λαμβάνει ή ορίζει ένα email που θα εμφανίζεται στη signature line.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
