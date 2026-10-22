---
title: "FormFieldSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει ιδιότητες υπογραφής πεδίου φόρμας."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Περιέχει ιδιότητες υπογραφής πεδίου φόρμας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Καθορίζει μοναδικό όνομα πεδίου φόρμας. |
| [setName(String value)](#setName-java.lang.String-) | Καθορίζει μοναδικό όνομα πεδίου φόρμας. |
| [getType()](#getType--) | Καθορίζει τύπο πεδίου φόρμας. |
| [getValue()](#getValue--) | Καθορίζει αντικείμενο δεδομένων πεδίου φόρμας. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Καθορίζει αντικείμενο δεδομένων πεδίου φόρμας. |
| [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
| [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
| [deepClone()](#deepClone--) | Κλωνοποιεί το αντίγραφο της FormField Signature. |
### getName() {#getName--}
```
public final String getName()
```


Καθορίζει μοναδικό όνομα πεδίου φόρμας.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Καθορίζει μοναδικό όνομα πεδίου φόρμας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Καθορίζει τύπο πεδίου φόρμας.

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Καθορίζει αντικείμενο δεδομένων πεδίου φόρμας.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Καθορίζει αντικείμενο δεδομένων πεδίου φόρμας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

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


Κλωνοποιεί το αντίγραφο της FormField Signature.

**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένη παρουσία υπογραφής FormField.
