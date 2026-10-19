---
title: "SpreadsheetMetadataSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες υπογραφής μεταδεδομένων λογιστικού φύλλου."
type: docs
weight: 17
url: /el/java/com.groupdocs.signature.domain.signatures.metadata/spreadsheetmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class SpreadsheetMetadataSignature extends MetadataSignature
```

Περιέχει ιδιότητες υπογραφής μεταδεδομένων λογιστικού φύλλου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetMetadataSignature(String name)](#SpreadsheetMetadataSignature-java.lang.String-) | Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένο όνομα και κενή τιμή. |
|
|  | [SpreadsheetMetadataSignature(String name, Object value)](#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-) | Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένες τιμές. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [deepClone()](#deepClone--) | Κλωνοποιεί το στιγμιότυπο της Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Κλωνοποιεί το στιγμιότυπο του Spreadsheet Metadata Signature με την δεδομένη τιμή. |
|
|  | [toString()](#toString--) | Μετατρέπει σε String με την υπερκαθορισμένη μέθοδο ToString() |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Μετατρέπει σε String με καθορισμένη μορφή |
|
### SpreadsheetMetadataSignature(String name) {#SpreadsheetMetadataSignature-java.lang.String-}
```
public SpreadsheetMetadataSignature(String name)
```


Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένο όνομα και κενή τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του Spreadsheet Metadata Signature. |
|

### SpreadsheetMetadataSignature(String name, Object value) {#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-}
```
public SpreadsheetMetadataSignature(String name, Object value)
```


Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένες τιμές.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα του αντικειμένου υπογραφής μεταδεδομένων. |
|
|  | τιμή | java.lang.Object | Τιμή της υπογραφής μεταδεδομένων. |
|

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


Κλωνοποιεί το στιγμιότυπο του Spreadsheet Metadata Signature με την δεδομένη τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.Object | Τιμή για νέο κλωνοποιημένο αντικείμενο. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toString() {#toString--}
```
public String toString()
```


Μετατρέπει σε String με την υπερκαθορισμένη μέθοδο ToString()


**Returns:**
java.lang.String - Επιστρέφει την τιμή της υπογραφής Metadata ως String.

<br />

*** ** * ** ***

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False". Για άλλου τύπου δεδομένα θα χρησιμοποιηθεί ο προεπιλεγμένος πάροχος μορφοποίησης δεδομένων.

<br />


### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Μετατρέπει σε String με καθορισμένη μορφή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μορφή | java.lang.String | Συμβολοσειρά μορφής δεδομένων. |
|
|  | πάροχος | com.aspose.ms.System.IFormatProvider | Πάροχος μορφοποίησης δεδομένων για χρήση σε λειτουργίες μετατροπής δεδομένων. |

<br />

*** ** * ** ***

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False".

<br />

|

**Returns:**
java.lang.String - Επιστρέφει την τιμή της υπογραφής Metadata ως String.

