---
title: "MetadataSearchOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αναπαριστά αφηρημένες επιλογές αναζήτησης για υπογραφές μεταδεδομένων."
type: docs
weight: 15
url: /el/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Αναπαριστά αφηρημένες επιλογές αναζήτησης για υπογραφές μεταδεδομένων.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SearchMetadataOptions με προεπιλεγμένες τιμές. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Καθορίζει το όνομα της υπογραφής Metadata εάν πρέπει να αναζητηθεί και να ταιριάξει. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Καθορίζει το όνομα της υπογραφής Metadata εάν πρέπει να αναζητηθεί και να ταιριάξει. |
|
|  | [getNameMatchType()](#getNameMatchType--) | Λαμβάνει ή ορίζει την αναζήτηση Match Type ονόματος Metadata. |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | Λαμβάνει ή ορίζει την αναζήτηση Match Type ονόματος Metadata. |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Δείχνει εάν οι ενσωματωμένες ιδιότητες εγγράφου όπως στατιστικά εγγράφου, πληροφορίες κ.λπ. πρέπει να συμπεριληφθούν στο αποτέλεσμα της αναζήτησης. |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Δείχνει εάν οι ενσωματωμένες ιδιότητες εγγράφου όπως στατιστικά εγγράφου, πληροφορίες κ.λπ. πρέπει να συμπεριληφθούν στο αποτέλεσμα της αναζήτησης. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code. |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SearchMetadataOptions με προεπιλεγμένες τιμές.


### getName() {#getName--}
```
public final String getName()
```


Καθορίζει το όνομα της υπογραφής Metadata εάν πρέπει να αναζητηθεί και να ταιριάξει.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Καθορίζει το όνομα της υπογραφής Metadata εάν πρέπει να αναζητηθεί και να ταιριάξει.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Λαμβάνει ή ορίζει την αναζήτηση Match Type ονόματος Metadata. Χρησιμοποιείται μόνο όταν έχει οριστεί η ιδιότητα Name.


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Λαμβάνει ή ορίζει την αναζήτηση Match Type ονόματος Metadata. Χρησιμοποιείται μόνο όταν έχει οριστεί η ιδιότητα Name.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Δείχνει εάν οι ενσωματωμένες ιδιότητες εγγράφου όπως στατιστικά εγγράφου, πληροφορίες κ.λπ. πρέπει να συμπεριληφθούν στο αποτέλεσμα της αναζήτησης.
Αυτή η σημαία έχει νόημα για τύπους αρχείων Presentation, Spreadhsheet και Word Processing.


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Δείχνει εάν οι ενσωματωμένες ιδιότητες εγγράφου όπως στατιστικά εγγράφου, πληροφορίες κ.λπ. πρέπει να συμπεριληφθούν στο αποτέλεσμα της αναζήτησης.
Αυτή η σημαία έχει νόημα για τύπους αρχείων Presentation, Spreadhsheet και Word Processing.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

