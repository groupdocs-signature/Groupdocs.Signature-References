---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου κειμένου για έγγραφο PDF"
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου κειμένου για έγγραφο PDF
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Δημιουργεί PdfTextFormFieldSignature με προκαθορισμένο όνομα. |
| [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Δημιουργεί PdfTextFormFieldSignature με προκαθορισμένο όνομα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getText()](#getText--) | Λαμβάνει ή ορίζει το κείμενο της εισόδου κειμένου πεδίου φόρμας. |
| [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή ορίζει το κείμενο της εισόδου κειμένου πεδίου φόρμας. |
| [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
| [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
| [deepClone()](#deepClone--) | Κλωνοποιεί το αντίγραφο της FormField Signature. |
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Δημιουργεί PdfTextFormFieldSignature με προκαθορισμένο όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Δημιουργεί PdfTextFormFieldSignature με προκαθορισμένο όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
| κείμενο | java.lang.String | Κείμενο του αντικειμένου πεδίου φόρμας. |

### getText() {#getText--}
```
public final String getText()
```


Λαμβάνει ή ορίζει το κείμενο της εισόδου κειμένου πεδίου φόρμας.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Λαμβάνει ή ορίζει το κείμενο της εισόδου κειμένου πεδίου φόρμας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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
