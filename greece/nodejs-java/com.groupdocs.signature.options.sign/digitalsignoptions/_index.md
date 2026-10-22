---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις επιλογές ψηφιακής υπογραφής."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Αντιπροσωπεύει τις επιλογές ψηφιακής υπογραφής.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DigitalSignOptions()](#DigitalSignOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με προεπιλεγμένες τιμές. |
| [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού. |
| [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού. |
| [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και αρχείο εικόνας. |
| [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και ροή εικόνας. |
| [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού και αρχείο εικόνας. |
| [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού και ροή εικόνας. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getReason()](#getReason--) | Λαμβάνει ή ορίζει το λόγο της υπογραφής. |
| [setReason(String value)](#setReason-java.lang.String-) | Λαμβάνει ή ορίζει το λόγο της υπογραφής. |
| [getContact()](#getContact--) | Λαμβάνει ή ορίζει την επαφή της υπογραφής. |
| [setContact(String value)](#setContact-java.lang.String-) | Λαμβάνει ή ορίζει την επαφή της υπογραφής. |
| [getLocation()](#getLocation--) | Λαμβάνει ή ορίζει την τοποθεσία της υπογραφής. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Λαμβάνει ή ορίζει την τοποθεσία της υπογραφής. |
| [getPassword()](#getPassword--) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης του ψηφιακού πιστοποιητικού. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης του ψηφιακού πιστοποιητικού. |
| [getSignature()](#getSignature--) | Λαμβάνει ή ορίζει τις ιδιότητες της ψηφιακής υπογραφής εγγράφου. |
| [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Λαμβάνει ή ορίζει τις ιδιότητες της ψηφιακής υπογραφής εγγράφου. |
| [getCertificateFilePath()](#getCertificateFilePath--) | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου ψηφιακού πιστοποιητικού. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Λαμβάνει ή ορίζει το GUID του αρχείου ψηφιακού πιστοποιητικού. |
| [getCertificateStream()](#getCertificateStream--) | Λαμβάνει ή ορίζει τη ροή του ψηφιακού πιστοποιητικού. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Λαμβάνει ή ορίζει τη ροή του ψηφιακού πιστοποιητικού. |
| [getVisible()](#getVisible--) | Λαμβάνει ή ορίζει την ορατότητα της υπογραφής. |
| [setVisible(boolean value)](#setVisible-boolean-) | Λαμβάνει ή ορίζει την ορατότητα της υπογραφής. |
| [getXAdESType()](#getXAdESType--) | Τύπος XAdES  XAdESType . |
| [setXAdESType(int value)](#setXAdESType-int-) | Τύπος XAdES  XAdESType . |
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά. |
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με προεπιλεγμένες τιμές.

### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Διαδρομή αρχείου ψηφιακού πιστοποιητικού |

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Ροή ψηφιακού πιστοποιητικού |

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και αρχείο εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Διαδρομή αρχείου ψηφιακού πιστοποιητικού |
| imageFilePath | java.lang.String | Διαδρομή αρχείου εικόνας εμφάνισης υπογραφής |

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και ροή εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Διαδρομή αρχείου ψηφιακού πιστοποιητικού |
| appearenceImageStream | java.io.InputStream | Ροή εικόνας εμφάνισης υπογραφής |

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού και αρχείο εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Ροή ψηφιακού πιστοποιητικού |
| imageFilePath | java.lang.String | Διαδρομή αρχείου εικόνας εμφάνισης υπογραφής |

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού και ροή εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Ροή ψηφιακού πιστοποιητικού |
| appearenceImageStream | java.io.InputStream | Ροή εικόνας εμφάνισης υπογραφής |

### getReason() {#getReason--}
```
public final String getReason()
```


Λαμβάνει ή ορίζει το λόγο της υπογραφής.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Λαμβάνει ή ορίζει το λόγο της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Λαμβάνει ή ορίζει την επαφή της υπογραφής.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Λαμβάνει ή ορίζει την επαφή της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Λαμβάνει ή ορίζει την τοποθεσία της υπογραφής.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Λαμβάνει ή ορίζει την τοποθεσία της υπογραφής.

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

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Λαμβάνει ή ορίζει τις ιδιότητες της ψηφιακής υπογραφής εγγράφου.

**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Λαμβάνει ή ορίζει τις ιδιότητες της ψηφιακής υπογραφής εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Λαμβάνει ή ορίζει τη διαδρομή αρχείου ψηφιακού πιστοποιητικού. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί CertificateStream.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Λαμβάνει ή ορίζει το GUID του αρχείου ψηφιακού πιστοποιητικού. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί CertificateStream.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Λαμβάνει ή ορίζει τη ροή ψηφιακού πιστοποιητικού. Εάν αυτή η ιδιότητα έχει καθοριστεί, χρησιμοποιείται πάντα αντί για CertificateGuid.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Λαμβάνει ή ορίζει τη ροή ψηφιακού πιστοποιητικού. Εάν αυτή η ιδιότητα έχει καθοριστεί, χρησιμοποιείται πάντα αντί για CertificateGuid.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Λαμβάνει ή ορίζει την ορατότητα της υπογραφής.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Λαμβάνει ή ορίζει την ορατότητα της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


Τύπος XAdES  XAdESType . Η προεπιλεγμένη τιμή είναι None (το XAdES είναι απενεργοποιημένο). Αυτή τη στιγμή ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα Spreadsheet στο .NET Framework (όχι στο .NET Standard).

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


Τύπος XAdES  XAdESType . Η προεπιλεγμένη τιμή είναι None (το XAdES είναι απενεργοποιημένο). Αυτή τη στιγμή ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα Spreadsheet στο .NET Framework (όχι στο .NET Standard).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Παρακάμπτει τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
