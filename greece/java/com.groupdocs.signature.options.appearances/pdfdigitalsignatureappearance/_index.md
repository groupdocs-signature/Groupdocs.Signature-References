---
title: "PdfDigitalSignatureAppearance"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιγράφει την εμφάνιση της Ψηφιακής Υπογραφής σε έγγραφα PDF."
type: docs
weight: 12
url: /el/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Περιγράφει την εμφάνιση της Ψηφιακής Υπογραφής σε έγγραφα PDF.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Δημιουργεί αντικείμενο εμφάνισης υπογραφής με προεπιλεγμένες τιμές. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | Λαμβάνει ή ορίζει την ετικέτα πληροφοριών επαφής. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Λαμβάνει ή ορίζει την ετικέτα πληροφοριών επαφής. |
|
|  | [getReasonLabel()](#getReasonLabel--) | Λαμβάνει ή ορίζει την ετικέτα λόγου. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Λαμβάνει ή ορίζει την ετικέτα λόγου. |
|
|  | [getLocationLabel()](#getLocationLabel--) | Λαμβάνει ή ορίζει την ετικέτα τοποθεσίας. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Λαμβάνει ή ορίζει την ετικέτα τοποθεσίας. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Λαμβάνει ή ορίζει την ετικέτα ψηφιακής υπογραφής. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Λαμβάνει ή ορίζει την ετικέτα ψηφιακής υπογραφής. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Λαμβάνει ή ορίζει την ετικέτα ημερομηνίας υπογραφής. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Λαμβάνει ή ορίζει την ετικέτα ημερομηνίας υπογραφής. |
|
|  | [getBackground()](#getBackground--) | Λάβετε ή ορίστε το χρώμα φόντου της εμφάνισης της υπογραφής. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | Λάβετε ή ορίστε το χρώμα φόντου της εμφάνισης της υπογραφής. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | Λάβετε ή ορίστε το χρώμα φόντου της εμφάνισης της υπογραφής. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | Λαμβάνει ή ορίζει το όνομα οικογένειας γραμματοσειράς για την εμφάνιση των ετικετών. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα οικογένειας γραμματοσειράς για την εμφάνιση των ετικετών. |
|
|  | [getFontSize()](#getFontSize--) | Λαμβάνει ή ορίζει το μέγεθος γραμματοσειράς για την εμφάνιση των ετικετών. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | Λαμβάνει ή ορίζει το μέγεθος γραμματοσειράς για την εμφάνιση των ετικετών. |
|
|  | [getForeground()](#getForeground--) | Λάβετε ή ορίστε το χρώμα κειμένου προσκηνίου της εμφάνισης της υπογραφής. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | Λάβετε ή ορίστε το χρώμα κειμένου προσκηνίου της εμφάνισης της υπογραφής. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | Λάβετε ή ορίστε το χρώμα κειμένου προσκηνίου της εμφάνισης της υπογραφής. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Δημιουργεί αντικείμενο εμφάνισης υπογραφής με προεπιλεγμένες τιμές.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Λαμβάνει ή ορίζει την ετικέτα πληροφοριών επαφής. Προεπιλεγμένη τιμή: "Contact".
εάν αυτή η τιμή είναι κενή, τότε δεν θα εμφανιστεί ετικέτα επαφής στην περιοχή ψηφιακής υπογραφής.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Λαμβάνει ή ορίζει την ετικέτα πληροφοριών επαφής. Προεπιλεγμένη τιμή: "Contact".
εάν αυτή η τιμή είναι κενή, τότε δεν θα εμφανιστεί ετικέτα επαφής στην περιοχή ψηφιακής υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Λαμβάνει ή ορίζει την ετικέτα λόγου. Προεπιλεγμένη τιμή: "Reason".
εάν αυτή η τιμή είναι κενή, τότε δεν θα εμφανιστεί ετικέτα λόγου στην περιοχή ψηφιακής υπογραφής.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Λαμβάνει ή ορίζει την ετικέτα λόγου. Προεπιλεγμένη τιμή: "Reason".
εάν αυτή η τιμή είναι κενή, τότε δεν θα εμφανιστεί ετικέτα λόγου στην περιοχή ψηφιακής υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Λαμβάνει ή ορίζει την ετικέτα τοποθεσίας. Προεπιλεγμένη τιμή: "Location".
εάν αυτή η τιμή είναι κενή, τότε δεν θα εμφανιστεί ετικέτα τοποθεσίας στην περιοχή ψηφιακής υπογραφής.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Λαμβάνει ή ορίζει την ετικέτα τοποθεσίας. Προεπιλεγμένη τιμή: "Location".
εάν αυτή η τιμή είναι κενή, τότε δεν θα εμφανιστεί ετικέτα τοποθεσίας στην περιοχή ψηφιακής υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Λαμβάνει ή ορίζει την ετικέτα ψηφιακής υπογραφής. Προεπιλεγμένη τιμή: "Digitally signed by".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Λαμβάνει ή ορίζει την ετικέτα ψηφιακής υπογραφής. Προεπιλεγμένη τιμή: "Digitally signed by".


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Λαμβάνει ή ορίζει την ετικέτα ημερομηνίας υπογραφής. Προεπιλεγμένη τιμή: "Date".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Λαμβάνει ή ορίζει την ετικέτα ημερομηνίας υπογραφής. Προεπιλεγμένη τιμή: "Date".


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Λάβετε ή ορίστε το χρώμα φόντου της εμφάνισης της υπογραφής.
Από προεπιλογή η τιμή είναι SystemColors.Windows


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Λάβετε ή ορίστε το χρώμα φόντου της εμφάνισης της υπογραφής.
Από προεπιλογή η τιμή είναι SystemColors.Windows


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Λάβετε ή ορίστε το χρώμα φόντου της εμφάνισης της υπογραφής.
Από προεπιλογή η τιμή είναι SystemColors.Windows


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Λαμβάνει ή ορίζει το όνομα οικογένειας γραμματοσειράς για την εμφάνιση των ετικετών. Προεπιλεγμένη τιμή είναι "Arial".


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Λαμβάνει ή ορίζει το όνομα οικογένειας γραμματοσειράς για την εμφάνιση των ετικετών. Προεπιλεγμένη τιμή είναι "Arial".


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Λαμβάνει ή ορίζει το μέγεθος γραμματοσειράς για την εμφάνιση των ετικετών. Προεπιλεγμένη τιμή είναι 10.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Λαμβάνει ή ορίζει το μέγεθος γραμματοσειράς για την εμφάνιση των ετικετών. Προεπιλεγμένη τιμή είναι 10.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Λάβετε ή ορίστε το χρώμα κειμένου προσκηνίου της εμφάνισης της υπογραφής.
Από προεπιλογή η τιμή είναι Color.FromArgb(76, 100, 255)


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Λάβετε ή ορίστε το χρώμα κειμένου προσκηνίου της εμφάνισης της υπογραφής.
Από προεπιλογή η τιμή είναι Color.FromArgb(76, 100, 255)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Λάβετε ή ορίστε το χρώμα κειμένου προσκηνίου της εμφάνισης της υπογραφής.
Από προεπιλογή η τιμή είναι Color.FromArgb(76, 100, 255)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

