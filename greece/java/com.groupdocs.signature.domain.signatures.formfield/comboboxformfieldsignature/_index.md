---
title: "ComboboxFormFieldSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου τύπου combo-box."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου τύπου combo-box.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Δημιουργεί το ComboboxFormFieldSignature με προεπιλεγμένο όνομα. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Δημιουργεί το ComboboxFormFieldSignature με προεπιλεγμένο όνομα και λίστα επιλογών. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Δημιουργεί το ComboboxFormFieldSignature με προεπιλεγμένο όνομα, λίστα επιλογών και επιλεγμένη τιμή. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSelected()](#getSelected--) | Λαμβάνει ή ορίζει την επιλεγμένη τιμή. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Λαμβάνει ή ορίζει την επιλεγμένη τιμή. |
|
|  | [getItems()](#getItems--) | Λαμβάνει ή ορίζει τη λίστα επιλογών του combo-box. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Λαμβάνει ή ορίζει τη λίστα επιλογών του combo-box. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιεί την παρουσία του FormField Signature. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Δημιουργεί το ComboboxFormFieldSignature με προεπιλεγμένο όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Δημιουργεί το ComboboxFormFieldSignature με προεπιλεγμένο όνομα και λίστα επιλογών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
|
|  | items | java.util.List<java.lang.String> | Τιμές της λίστας combo-box. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Δημιουργεί το ComboboxFormFieldSignature με προεπιλεγμένο όνομα, λίστα επιλογών και επιλεγμένη τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
|
|  | items | java.util.List<java.lang.String> | Τιμές της λίστας combo-box. |
|
|  | selected | java.lang.Object | Επιλεγμένη τιμή. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Λαμβάνει ή ορίζει την επιλεγμένη τιμή.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Λαμβάνει ή ορίζει την επιλεγμένη τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Λαμβάνει ή ορίζει τη λίστα επιλογών του combo-box.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Λαμβάνει ή ορίζει τη λίστα επιλογών του combo-box.


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

