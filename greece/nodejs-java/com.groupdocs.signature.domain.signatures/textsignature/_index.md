---
title: "TextSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει ιδιότητες Text signature."
type: docs
weight: 18
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Περιέχει ιδιότητες Text signature.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Αρχικοποιήστε το αντικείμενο TextSignature με το αναγνωριστικό υπογραφής που ελήφθη μετά τη διαδικασία αναζήτησης. |
| [TextSignature()](#TextSignature--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getText()](#getText--) | Καθορίζει το κείμενο στην υπογραφή. |
| [setText(String value)](#setText-java.lang.String-) | Καθορίζει το κείμενο στην υπογραφή. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Καθορίζει την υλοποίηση της υπογραφής κειμένου. |
| [getNative()](#getNative--) | Καθορίζει το εγγενές χαρακτηριστικό. |
| [setNative(boolean value)](#setNative-boolean-) | Καθορίζει το εγγενές χαρακτηριστικό. |
| [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
| [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
| [deepClone()](#deepClone--) | Κλωνοποιήστε το αντίγραφο της Text Signature. |
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Αρχικοποιήστε το αντικείμενο TextSignature με το αναγνωριστικό υπογραφής που ελήφθη μετά τη διαδικασία αναζήτησης. Αυτό το μοναδικό αναγνωριστικό χρησιμοποιείται για την εύρεση πρόσθετων ιδιοτήτων για αυτήν την υπογραφή από το επίπεδο πληροφοριών υπογραφής του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureId | java.lang.String | Μοναδικό αναγνωριστικό υπογραφής που λαμβάνεται με τη μέθοδο υπογραφής ή αναζήτησης. |

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Καθορίζει το κείμενο στην υπογραφή.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Καθορίζει το κείμενο στην υπογραφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Καθορίζει την υλοποίηση της υπογραφής κειμένου.

**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Καθορίζει το εγγενές χαρακτηριστικό. Είναι true εάν η υπογραφή είναι ειδική για το έγγραφο.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Καθορίζει το εγγενές χαρακτηριστικό. Είναι true εάν η υπογραφή είναι ειδική για το έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| υπογραφή | java.lang.Object | Αντικείμενο υπογραφής για σύγκριση. |

**Returns:**
boolean - Επιστρέφει true εάν το δοσμένο αντικείμενο υπογραφής έχει τον ίδιο τύπο και όλες οι ιδιότητές του είναι ίσες με τις ιδιότητες αυτού του αντικειμένου.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Αντικαθιστά τη μέθοδο GetHashCode

**Returns:**
int - Κώδικας κατακερματισμού υπογραφής
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Κλωνοποιήστε το αντίγραφο της Text Signature.

**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένο αντίγραφο της Text Signature.
