---
title: "PresentationMetadataSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει ιδιότητες υπογραφής μεταδεδομένων παρουσίασης."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

Περιέχει ιδιότητες υπογραφής μεταδεδομένων παρουσίασης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | Δημιουργεί Presentation Metadata Signature με προ-ορισμένο όνομα και κενή τιμή. |
| [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | Δημιουργεί Presentation Metadata Signature με προ-ορισμένες τιμές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Κλωνοποιεί την παρουσία του Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Κλωνοποιεί την παρουσίαση Slides Metadata Signature με την δοθείσα τιμή. |
| [toString()](#toString--) | Μετατρέπει σε String με την υπερφόρτωση της μεθόδου ToString() |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Μετατρέπει σε String με καθορισμένη μορφή |
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


Δημιουργεί Presentation Metadata Signature με προ-ορισμένο όνομα και κενή τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα υπογραφής μεταδεδομένων παρουσίασης |

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


Δημιουργεί Presentation Metadata Signature με προ-ορισμένες τιμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου υπογραφής Metadata |
| τιμή | java.lang.Object | Τιμή του Metadata υπογραφής |

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


Κλωνοποιεί την παρουσίαση Slides Metadata Signature με την δοθείσα τιμή.

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
