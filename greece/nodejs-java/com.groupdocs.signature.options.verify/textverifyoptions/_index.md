---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Διατηρεί επιλογές για επαλήθευση υπογραφής κειμένου εγγράφου."
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Διατηρεί επιλογές για επαλήθευση υπογραφής κειμένου εγγράφου.

--------------------

**Learn more**

 *  Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/
[Advanced usage of eVerification Barcode signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-text-signatures/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextVerifyOptions()](#TextVerifyOptions--) | Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με προεπιλεγμένες τιμές. |
| [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με κείμενο επαλήθευσης. |
| [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με την ιδιότητα Text για επαλήθευση και υλοποίηση υπογραφής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getText()](#getText--) | Καθορίστε το Κείμενο Υπογραφής εάν πρέπει να επαληθευτεί. |
| [setText(String value)](#setText-java.lang.String-) | Καθορίστε το Κείμενο Υπογραφής εάν πρέπει να επαληθευτεί. |
| [getMatchType()](#getMatchType--) | Λαμβάνει ή ορίζει την επαλήθευση τύπου αντιστοίχισης κειμένου. |
| [setMatchType(int value)](#setMatchType-int-) | Λαμβάνει ή ορίζει την επαλήθευση τύπου αντιστοίχισης κειμένου. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Τύπος υπογραφής προς επαλήθευση. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Τύπος υπογραφής προς επαλήθευση. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας για επαλήθευση. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας για επαλήθευση. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για επαλήθευση. |
| [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για επαλήθευση. |
| [getSignatureID()](#getSignatureID--) | Καθορίστε το ID της Υπογραφής Κειμένου μεγαλύτερο του μηδενός εάν πρέπει να επαληθευτεί. |
| [setSignatureID(int value)](#setSignatureID-int-) | Καθορίστε το ID της Υπογραφής Κειμένου μεγαλύτερο του μηδενός εάν πρέπει να επαληθευτεί. |
| [toString()](#toString--) | Αντικαθιστά τη μετατροπή σε συμβολοσειρά. |
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με προεπιλεγμένες τιμές.

### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με κείμενο επαλήθευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο προς επαλήθευση |

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με την ιδιότητα Text για επαλήθευση και υλοποίηση υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο προς επαλήθευση. |
| υλοποίηση | int | Τύπος υλοποίησης υπογραφής. |

### getText() {#getText--}
```
public final String getText()
```


Καθορίστε το Κείμενο Υπογραφής εάν πρέπει να επαληθευτεί.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Καθορίστε το Κείμενο Υπογραφής εάν πρέπει να επαληθευτεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Λαμβάνει ή ορίζει την επαλήθευση τύπου αντιστοίχισης κειμένου.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Λαμβάνει ή ορίζει την επαλήθευση τύπου αντιστοίχισης κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Τύπος υπογραφής προς επαλήθευση.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Τύπος υπογραφής προς επαλήθευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας για επαλήθευση. Εάν αυτή η ιδιότητα οριστεί, το κείμενο θα βρεθεί μόνο σε πεδία φόρμας κειμένου.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας για επαλήθευση. Εάν αυτή η ιδιότητα οριστεί, το κείμενο θα βρεθεί μόνο σε πεδία φόρμας κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για επαλήθευση. Εάν αυτή η ιδιότητα οριστεί, το κείμενο θα βρεθεί μόνο σε πεδία φόρμας κειμένου.

**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για επαλήθευση. Εάν αυτή η ιδιότητα οριστεί, το κείμενο θα βρεθεί μόνο σε πεδία φόρμας κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Καθορίστε το ID της Υπογραφής Κειμένου μεγαλύτερο του μηδενός εάν πρέπει να επαληθευτεί. Αυτή η ιδιότητα υποστηρίζεται μόνο για έγγραφα Pdf.

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Καθορίστε το ID της Υπογραφής Κειμένου μεγαλύτερο του μηδενός εάν πρέπει να επαληθευτεί. Αυτή η ιδιότητα υποστηρίζεται μόνο για έγγραφα Pdf.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Αντικαθιστά τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
