---
title: "DigitalSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες ψηφιακής υπογραφής."
type: docs
weight: 12
url: /el/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Περιέχει ιδιότητες ψηφιακής υπογραφής.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | Αρχικοποιήστε την ψηφιακή υπογραφή με προεπιλεγμένες παραμέτρους. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Αρχικοποιήστε την ψηφιακή υπογραφή με γνωστό το SignatureId. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Δημιουργήστε ψηφιακή υπογραφή με το συγκεκριμένο πιστοποιητικό. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Δημιουργήστε ψηφιακή υπογραφή βασισμένη στο πιστοποιητικό X509Certificate και το PrivateKey. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Ανακτά ή ορίζει το πιστοποιητικό KeyStore. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Ανακτά ή ορίζει το πιστοποιητικό KeyStore. |
|
|  | [getX509Certificate()](#getX509Certificate--) | Λαμβάνει ή ορίζει το πιστοποιητικό X509. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Λαμβάνει ή ορίζει το πιστοποιητικό X509. |
|
|  | [getPrivateKey()](#getPrivateKey--) | Λαμβάνει ή ορίζει το PrivateKey του πιστοποιητικού. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Λαμβάνει ή ορίζει το PrivateKey του πιστοποιητικού. |
|
|  | [getCertificateName()](#getCertificateName--) | Λαμβάνει ή ορίζει το όνομα του πιστοποιητικού X509. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του πιστοποιητικού X509. |
|
|  | [getComments()](#getComments--) | Λαμβάνει ή ορίζει το σχόλιο σκοπού υπογραφής. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Λαμβάνει ή ορίζει το σχόλιο σκοπού υπογραφής. |
|
|  | [isValid()](#isValid--) | Παραμένει true εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Παραμένει true εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί. |
|
|  | [getSignTime()](#getSignTime--) | Λαμβάνει ή ορίζει την ώρα που υπογράφηκε το έγγραφο. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | Λαμβάνει ή ορίζει την ώρα που υπογράφηκε το έγγραφο. |
|
|  | [getXAdESType()](#getXAdESType--) | Τύπος XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | Τύπος XAdES |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | Λαμβάνει το αποτύπωμα ενός πιστοποιητικού. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιήστε την παρουσία Barcode Signature. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | Φορτώνει την ψηφιακή υπογραφή από όλες τις αποθήκες πιστοποιητικών X509 του συστήματος. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Φορτώνει την ψηφιακή υπογραφή από την παρεχόμενη αποθήκη πιστοποιητικών X509. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Αρχικοποιήστε την ψηφιακή υπογραφή με προεπιλεγμένες παραμέτρους.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Αρχικοποιήστε την ψηφιακή υπογραφή με γνωστό το SignatureId.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Δημιουργήστε ψηφιακή υπογραφή με το συγκεκριμένο πιστοποιητικό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πιστοποιητικό | java.security.KeyStore | Πιστοποιητικό X509. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Δημιουργήστε ψηφιακή υπογραφή βασισμένη στο πιστοποιητικό X509Certificate και το PrivateKey.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | Πιστοποιητικό X509Certificate. |
|
|  | key | java.security.PrivateKey | PrivateKey του πιστοποιητικού. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Ανακτά ή ορίζει το πιστοποιητικό KeyStore.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Ανακτά ή ορίζει το πιστοποιητικό KeyStore.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Λαμβάνει ή ορίζει το πιστοποιητικό X509.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Λαμβάνει ή ορίζει το πιστοποιητικό X509.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Λαμβάνει ή ορίζει το PrivateKey του πιστοποιητικού.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Λαμβάνει ή ορίζει το PrivateKey του πιστοποιητικού.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Λαμβάνει ή ορίζει το όνομα του πιστοποιητικού X509.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Λαμβάνει ή ορίζει το όνομα του πιστοποιητικού X509.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Λαμβάνει ή ορίζει το σχόλιο σκοπού υπογραφής.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Λαμβάνει ή ορίζει το σχόλιο σκοπού υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Παραμένει true εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Παραμένει true εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Λαμβάνει ή ορίζει την ώρα που υπογράφηκε το έγγραφο.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Λαμβάνει ή ορίζει την ώρα που υπογράφηκε το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


Τύπος XAdES
XAdESType
. Η προεπιλεγμένη τιμή είναι None (το XAdES είναι απενεργοποιημένο).
Προς το παρόν ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα Spreadsheet.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


Τύπος XAdES
XAdESType
. Η προεπιλεγμένη τιμή είναι None (το XAdES είναι απενεργοποιημένο).
Προς το παρόν ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα Spreadsheet.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Λαμβάνει το αποτύπωμα ενός πιστοποιητικού.


**Returns:**
java.lang.String
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


Κλωνοποιήστε την παρουσία Barcode Signature.


**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένο αντίτυπο Barcode Signature.

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Φορτώνει την ψηφιακή υπογραφή από όλες τις αποθήκες πιστοποιητικών X509 του συστήματος.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Επιστρέφει λίστα των [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Ψηφιακών Υπογραφών.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Φορτώνει την ψηφιακή υπογραφή από την παρεχόμενη αποθήκη πιστοποιητικών X509.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Επιστρέφει λίστα των [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Ψηφιακών Υπογραφών.

