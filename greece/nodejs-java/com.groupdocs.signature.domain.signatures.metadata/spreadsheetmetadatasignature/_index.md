---
title: "SpreadsheetMetadataSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει ιδιότητες υπογραφής μεταδεδομένων υπολογιστικού φύλλου."
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/spreadsheetmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class SpreadsheetMetadataSignature extends MetadataSignature
```

Περιέχει ιδιότητες υπογραφής μεταδεδομένων υπολογιστικού φύλλου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SpreadsheetMetadataSignature(String name)](#SpreadsheetMetadataSignature-java.lang.String-) | Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένο όνομα και κενή τιμή. |
| [SpreadsheetMetadataSignature(String name, Object value)](#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-) | Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένες τιμές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Κλωνοποιεί την παρουσία του Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Κλωνοποιεί το στιγμιότυπο Spreadsheet Metadata Signature με τη δεδομένη τιμή. |
| [toString()](#toString--) | Μετατρέπει σε String με την υπερφόρτωση της μεθόδου ToString() |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Μετατρέπει σε String με καθορισμένη μορφή |
### SpreadsheetMetadataSignature(String name) {#SpreadsheetMetadataSignature-java.lang.String-}
```
public SpreadsheetMetadataSignature(String name)
```


Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένο όνομα και κενή τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα Spreadsheet Metadata Signature. |

### SpreadsheetMetadataSignature(String name, Object value) {#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-}
```
public SpreadsheetMetadataSignature(String name, Object value)
```


Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένες τιμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου Metadata signature. |
| τιμή | java.lang.Object | Τιμή του Metadata signature. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Κλωνοποιεί την παρουσία του Metadata Signature.

**Returns:**
java.lang.Object - Επιστρέφει την κλωνοποιημένη παρουσία του Metadata Signature
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Κλωνοποιεί το στιγμιότυπο Spreadsheet Metadata Signature με τη δεδομένη τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object | Τιμή για το νέο κλωνοποιημένο αντικείμενο. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


Μετατρέπει σε String με την υπερφόρτωση της μεθόδου ToString()

**Returns:**
java.lang.String - Επιστρέφει την τιμή υπογραφής Metadata ως String.

--------------------

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False". Για άλλου τύπου δεδομένα θα χρησιμοποιηθεί ο προεπιλεγμένος πάροχος μορφοποίησης δεδομένων.
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Μετατρέπει σε String με καθορισμένη μορφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | java.lang.String | Συμβολοσειρά μορφής δεδομένων. |
|  | πάροχος | com.aspose.ms.System.IFormatProvider | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

--------------------

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False" |

**Returns:**
java.lang.String - Επιστρέφει την τιμή υπογραφής Metadata ως String.
