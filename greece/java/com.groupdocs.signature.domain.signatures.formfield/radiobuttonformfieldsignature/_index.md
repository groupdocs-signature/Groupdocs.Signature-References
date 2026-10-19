---
title: "RadioButtonFormFieldSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου τύπου radio-button."
type: docs
weight: 14
url: /el/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου τύπου radio-button.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Δημιουργεί το RadioButtonFieldSignature με προεπιλεγμένο όνομα. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Δημιουργεί RadioButtonFieldSignature με προεπιλεγμένο όνομα και λίστα στοιχείων. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Δημιουργεί RadioButtonFieldSignature με προεπιλεγμένο όνομα, λίστα στοιχείων και επιλεγμένη τιμή. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSelected()](#getSelected--) | Περιέχει την επιλεγμένη τιμή. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Περιέχει την επιλεγμένη τιμή. |
|
|  | [getItems()](#getItems--) | Λάβετε ή ορίστε τη λίστα επιλογών των Radio buttons. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Λάβετε ή ορίστε τη λίστα επιλογών των Radio buttons. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιεί την παρουσία του FormField Signature. |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Δημιουργεί το RadioButtonFieldSignature με προεπιλεγμένο όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Δημιουργεί RadioButtonFieldSignature με προεπιλεγμένο όνομα και λίστα στοιχείων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
|
|  | items | java.util.List<java.lang.String> | Τιμές της λίστας radio-button. |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Δημιουργεί RadioButtonFieldSignature με προεπιλεγμένο όνομα, λίστα στοιχείων και επιλεγμένη τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
|
|  | items | java.util.List<java.lang.String> | Τιμές της λίστας radio-button. |
|
|  | selected | java.lang.Object | Επιλεγμένη τιμή. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Περιέχει την επιλεγμένη τιμή.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Περιέχει την επιλεγμένη τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Λάβετε ή ορίστε τη λίστα επιλογών των Radio buttons.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Λάβετε ή ορίστε τη λίστα επιλογών των Radio buttons.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<java.lang.String> |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | υπογραφή | java.lang.Object | Αντικείμενο υπογραφής για σύγκριση. |
|

**Returns:**
boolean - Επιστρέφει true εάν το περασμένο αντικείμενο υπογραφής έχει τον ίδιο τύπο και όλες οι ιδιότητές του είναι ίσες με τις ιδιότητες αυτού του αντικειμένου.

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


Κλωνοποιεί την παρουσία του FormField Signature.


**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένη παρουσία του FormField Signature.

