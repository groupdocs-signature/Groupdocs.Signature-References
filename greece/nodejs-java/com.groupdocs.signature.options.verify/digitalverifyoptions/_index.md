---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Διατηρεί επιλογές για επαλήθευση ψηφιακής υπογραφής εγγράφου."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Διατηρεί επιλογές για επαλήθευση ψηφιακής υπογραφής εγγράφου.

--------------------

**Learn more**

 *  Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ][How to eVerification Digital signatures in a document]
 *  Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings


[How to eVerification Digital signatures in a document]: https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Δημιουργεί την επιλογή ψηφιακής επαλήθευσης με προεπιλεγμένες τιμές. |
| [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Δημιουργεί την επιλογή ψηφιακής επαλήθευσης με το δοσμένο GUID ψηφιακού πιστοποιητικού. |
| [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Δημιουργεί την επιλογή ψηφιακής επαλήθευσης με το δοσμένο ρεύμα πιστοποιητικού. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCertificate()](#getCertificate--) | Λάβετε το πιστοποιητικό X509Certificate2 από το GUID ή το ρεύμα του πιστοποιητικού. |
| [getPassword()](#getPassword--) | Κωδικός πρόσβασης του ψηφιακού πιστοποιητικού εάν απαιτείται. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Κωδικός πρόσβασης του ψηφιακού πιστοποιητικού εάν απαιτείται. |
| [getCertificateFilePath()](#getCertificateFilePath--) | GUID αρχείου του ψηφιακού πιστοποιητικού. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | GUID αρχείου του ψηφιακού πιστοποιητικού. |
| [getCertificateStream()](#getCertificateStream--) | Ρεύμα του ψηφιακού πιστοποιητικού. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Ρεύμα του ψηφιακού πιστοποιητικού. |
| [getComments()](#getComments--) | Σχόλια της ψηφιακής υπογραφής για επαλήθευση. |
| [setComments(String value)](#setComments-java.lang.String-) | Σχόλια της ψηφιακής υπογραφής για επαλήθευση. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Περιοχή ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Περιοχή ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | Περιοχή ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Περιοχή ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. |
| [getReason()](#getReason--) | Αιτία της ψηφιακής υπογραφής για επαλήθευση. |
| [setReason(String value)](#setReason-java.lang.String-) | Αιτία της ψηφιακής υπογραφής για επαλήθευση. |
| [getContact()](#getContact--) | Επαφή υπογραφής για επαλήθευση. |
| [setContact(String value)](#setContact-java.lang.String-) | Επαφή υπογραφής για επαλήθευση. |
| [getLocation()](#getLocation--) | Τοποθεσία υπογραφής για επαλήθευση. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Τοποθεσία υπογραφής για επαλήθευση. |
| [getSubjectName()](#getSubjectName--) | Διακριτικό όνομα υποκειμένου του πιστοποιητικού για επαλήθευση. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Διακριτικό όνομα υποκειμένου του πιστοποιητικού για επαλήθευση. |
| [getIssuerName()](#getIssuerName--) | Όνομα εκδότη του πιστοποιητικού για επαλήθευση. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Όνομα εκδότη του πιστοποιητικού για επαλήθευση. |
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Δημιουργεί την επιλογή ψηφιακής επαλήθευσης με προεπιλεγμένες τιμές.

### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Δημιουργεί την επιλογή ψηφιακής επαλήθευσης με το δοσμένο GUID ψηφιακού πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateGuid | java.lang.String | Διαδρομή αρχείου προς το ψηφιακό πιστοποιητικό. |

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Δημιουργεί την επιλογή ψηφιακής επαλήθευσης με το δοσμένο ρεύμα πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Ρεύμα του πιστοποιητικού. |

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Λάβετε το πιστοποιητικό X509Certificate2 από το GUID ή το ρεύμα του πιστοποιητικού.

**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Κωδικός πρόσβασης του ψηφιακού πιστοποιητικού εάν απαιτείται.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Κωδικός πρόσβασης του ψηφιακού πιστοποιητικού εάν απαιτείται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


GUID αρχείου του ψηφιακού πιστοποιητικού.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


GUID αρχείου του ψηφιακού πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Ρεύμα του ψηφιακού πιστοποιητικού.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Ρεύμα του ψηφιακού πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Σχόλια της ψηφιακής υπογραφής για επαλήθευση.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Σχόλια της ψηφιακής υπογραφής για επαλήθευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Περιοχή ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. Η τιμή που μπορεί να είναι null θα αγνοηθεί.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Περιοχή ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. Η τιμή που μπορεί να είναι null θα αγνοηθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Περιοχή ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. Η τιμή που μπορεί να είναι null θα αγνοηθεί.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Περιοχή ημερομηνίας και ώρας της ψηφιακής υπογραφής για επαλήθευση. Η τιμή που μπορεί να είναι null θα αγνοηθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Αιτία της ψηφιακής υπογραφής για επαλήθευση.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Αιτία της ψηφιακής υπογραφής για επαλήθευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Επαφή υπογραφής για επαλήθευση.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Επαφή υπογραφής για επαλήθευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Τοποθεσία υπογραφής για επαλήθευση.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Τοποθεσία υπογραφής για επαλήθευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Διακριτικό όνομα υποκειμένου του πιστοποιητικού για επαλήθευση. Η τιμή είναι ευαίσθητη σε πεζά/κεφαλαία. Εάν αυτή η ιδιότητα οριστεί, η επαλήθευση θα ελέγξει αν το όνομα υποκειμένου της υπογραφής περιέχει ή ισούται με την περασμένη τιμή.

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Διακριτικό όνομα υποκειμένου του πιστοποιητικού για επαλήθευση. Η τιμή είναι ευαίσθητη σε πεζά/κεφαλαία. Εάν αυτή η ιδιότητα οριστεί, η επαλήθευση θα ελέγξει αν το όνομα υποκειμένου της υπογραφής περιέχει ή ισούται με την περασμένη τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Όνομα εκδότη του πιστοποιητικού για επαλήθευση. Η τιμή είναι ευαίσθητη σε πεζά/κεφαλαία. Εάν αυτή η ιδιότητα οριστεί, η επαλήθευση θα ελέγξει αν το όνομα εκδότη της υπογραφής περιέχει ή ισούται με την περασμένη τιμή.

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Όνομα εκδότη του πιστοποιητικού για επαλήθευση. Η τιμή είναι ευαίσθητη σε πεζά/κεφαλαία. Εάν αυτή η ιδιότητα οριστεί, η επαλήθευση θα ελέγξει αν το όνομα εκδότη της υπογραφής περιέχει ή ισούται με την περασμένη τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

