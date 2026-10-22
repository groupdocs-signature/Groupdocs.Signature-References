---
title: "DigitalVBA"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει την ψηφιακή υπογραφή για έργα VBA σε Φύλλα Εργασίας."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Αντιπροσωπεύει ψηφιακή υπογραφή για έργα VBA σε λογιστικά φύλλα. Παρέχει τη δυνατότητα υπογραφής του έργου VBA σε συγκεκριμένες μορφές εγγράφων λογιστικών φύλλων όπως Xlsm ή Xltm. Εάν προστεθούν πολλές επεκτάσεις DigitalVBA στο DigitalSignOptions.Extensions, μόνο η πρώτη συμμετέχει στην υπογραφή του εγγράφου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης DigitalVBA με αρχείο πιστοποιητικού. |
| [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης DigitalVBA με ροή πιστοποιητικού. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getComments()](#getComments--) | Λαμβάνει ή ορίζει τα σχόλια της υπογραφής. |
| [setComments(String value)](#setComments-java.lang.String-) | Λαμβάνει ή ορίζει τα σχόλια της υπογραφής. |
| [getPassword()](#getPassword--) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης του ψηφιακού πιστοποιητικού. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης του ψηφιακού πιστοποιητικού. |
| [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Λαμβάνει ή ορίζει τη ρύθμιση μόνο για υπογραφή έργου VBA. |
| [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Λαμβάνει ή ορίζει τη ρύθμιση μόνο για υπογραφή έργου VBA. |
| [getCertificateFilePath()](#getCertificateFilePath--) | Λαμβάνει τη διαδρομή του αρχείου ψηφιακού πιστοποιητικού. |
| [getCertificateStream()](#getCertificateStream--) | Λαμβάνει τη ροή του ψηφιακού πιστοποιητικού. |
| [release()](#release--) | Υπερκαλύπτει τη μέθοδο για εκκαθάριση πόρων μετά την υπογραφή. |
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Αρχικοποιεί ένα νέο παράδειγμα της κλάσης DigitalVBA με αρχείο πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Διαδρομή αρχείου ψηφιακού πιστοποιητικού |
| password | java.lang.String | Κωδικός πρόσβασης ψηφιακού πιστοποιητικού |

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Αρχικοποιεί ένα νέο παράδειγμα της κλάσης DigitalVBA με ροή πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Ροή ψηφιακού πιστοποιητικού |
| password | java.lang.String | Κωδικός πρόσβασης ψηφιακού πιστοποιητικού |

### getComments() {#getComments--}
```
public final String getComments()
```


Λαμβάνει ή ορίζει τα σχόλια της υπογραφής.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Λαμβάνει ή ορίζει τα σχόλια της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει ή ορίζει τον κωδικό πρόσβασης του ψηφιακού πιστοποιητικού.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Λαμβάνει ή ορίζει τον κωδικό πρόσβασης του ψηφιακού πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Λαμβάνει ή ορίζει τη ρύθμιση μόνο για υπογραφή έργου VBA. Εάν οριστεί σε true, το έγγραφο SpreadSheet δεν θα υπογραφεί, αλλά το έργο VBA θα υπογραφεί.

**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Λαμβάνει ή ορίζει τη ρύθμιση μόνο για υπογραφή έργου VBA. Εάν οριστεί σε true, το έγγραφο SpreadSheet δεν θα υπογραφεί, αλλά το έργο VBA θα υπογραφεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Λαμβάνει τη διαδρομή του αρχείου ψηφιακού πιστοποιητικού. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί CertificateStream.

**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Λαμβάνει τη ροή του ψηφιακού πιστοποιητικού. Εάν αυτή η ιδιότητα έχει καθοριστεί, χρησιμοποιείται πάντα αντί για CertificateFilePath.

**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Υπερκαλύπτει τη μέθοδο για εκκαθάριση πόρων μετά την υπογραφή.

