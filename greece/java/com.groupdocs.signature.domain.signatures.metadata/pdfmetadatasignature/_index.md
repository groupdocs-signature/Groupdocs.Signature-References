---
title: "PdfMetadataSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες υπογραφής μεταδεδομένων PDF."
type: docs
weight: 14
url: /el/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Περιέχει ιδιότητες υπογραφής μεταδεδομένων PDF.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Δημιουργεί υπογραφή Pdf Metadata με προκαθορισμένο όνομα και κενή τιμή |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Δημιουργεί υπογραφή Pdf Metadata με προκαθορισμένες τιμές |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Δημιουργεί υπογραφή Pdf Metadata με προκαθορισμένες τιμές |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | Η ετικέτα προθέματος του ονόματος της υπογραφής Pdf Metadata. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Η ετικέτα προθέματος του ονόματος της υπογραφής Pdf Metadata. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιεί το στιγμιότυπο της Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Κλωνοποιεί το στιγμιότυπο της Pdf Metadata Signature με την δεδομένη τιμή. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Δημιουργεί υπογραφή Pdf Metadata με προκαθορισμένο όνομα και κενή τιμή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα Pdf Metadata Signature |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Δημιουργεί υπογραφή Pdf Metadata με προκαθορισμένες τιμές


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου υπογραφής μεταδεδομένων |
|
|  | τιμή | java.lang.Object | Τιμή της υπογραφής μεταδεδομένων |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Δημιουργεί υπογραφή Pdf Metadata με προκαθορισμένες τιμές


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου υπογραφής μεταδεδομένων |
|
|  | τιμή | java.lang.Object | Τιμή της υπογραφής μεταδεδομένων |
|
|  | ετικέτα | java.lang.String | Πρόθεμα ετικέτας της υπογραφής μεταδεδομένων |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Η ετικέτα προθέματος του ονόματος της υπογραφής Pdf Metadata. Από προεπιλογή αυτή η ιδιότητα ορίζεται σε "xmp".
Οι πιθανές τιμές είναι


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Η ετικέτα προθέματος του ονόματος της υπογραφής Pdf Metadata. Από προεπιλογή αυτή η ιδιότητα ορίζεται σε "xmp".
Οι πιθανές τιμές είναι


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


Κλωνοποιεί το στιγμιότυπο της Metadata Signature.


**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένο αντικείμενο Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Κλωνοποιεί το στιγμιότυπο της Pdf Metadata Signature με την δεδομένη τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.Object | Τιμή για νέο κλωνοποιημένο αντικείμενο. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

