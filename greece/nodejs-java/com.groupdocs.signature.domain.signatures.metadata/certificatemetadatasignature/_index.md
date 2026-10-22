---
title: "CertificateMetadataSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει τις ιδιότητες της υπογραφής μεταδεδομένων πιστοποιητικού."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/certificatemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class CertificateMetadataSignature extends MetadataSignature
```

Περιέχει τις ιδιότητες της υπογραφής μεταδεδομένων πιστοποιητικού.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CertificateMetadataSignature(String name)](#CertificateMetadataSignature-java.lang.String-) | Δημιουργεί Certificate Metadata Signature με προκαθορισμένο όνομα και κενή τιμή. |
| [CertificateMetadataSignature(String name, Object value)](#CertificateMetadataSignature-java.lang.String-java.lang.Object-) | Δημιουργεί Certificate Metadata Signature με προκαθορισμένες τιμές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Κλωνοποιεί την παρουσία του Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Κλωνοποιήστε την παρουσία Certificate Metadata Signature με την δεδομένη τιμή. |
| [toString()](#toString--) | Μετατρέπει σε String με την υπερφόρτωση της μεθόδου ToString() |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Μετατρέπει σε String με καθορισμένη μορφή |
### CertificateMetadataSignature(String name) {#CertificateMetadataSignature-java.lang.String-}
```
public CertificateMetadataSignature(String name)
```


Δημιουργεί Certificate Metadata Signature με προκαθορισμένο όνομα και κενή τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Certificate Metadata Signature όνομα. |

### CertificateMetadataSignature(String name, Object value) {#CertificateMetadataSignature-java.lang.String-java.lang.Object-}
```
public CertificateMetadataSignature(String name, Object value)
```


Δημιουργεί Certificate Metadata Signature με προκαθορισμένες τιμές.

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


Κλωνοποιήστε την παρουσία Certificate Metadata Signature με την δεδομένη τιμή.

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
