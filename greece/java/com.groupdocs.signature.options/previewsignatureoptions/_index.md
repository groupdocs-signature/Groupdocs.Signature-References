---
title: "PreviewSignatureOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αναπαριστά τις επιλογές προεπισκόπησης υπογραφής."
type: docs
weight: 12
url: /el/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Αναπαριστά τις επιλογές προεπισκόπησης υπογραφής.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Αρχικοποιεί το αντικείμενο PreviewSignatureOptions. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | Μοναδική τιμή για τη διάκριση της υπογραφής. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Μοναδική τιμή για τη διάκριση της υπογραφής. |
|
|  | [getSignOptions()](#getSignOptions--) | Επιλογές υπογραφής για τη δημιουργία προεπισκόπησης. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Επιλογές υπογραφής για τη δημιουργία προεπισκόπησης. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Λαμβάνει ή ορίζει τη μορφή των εικόνων προεπισκόπησης. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Λαμβάνει ή ορίζει τη μορφή των εικόνων προεπισκόπησης. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Αρχικοποιεί το αντικείμενο PreviewSignatureOptions.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής για τη δημιουργία προεπισκόπησης. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Διεπαφή που ορίζει τη μέθοδο για τη δημιουργία ροής προεπισκόπησης σελίδας εξόδου. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Μοναδική τιμή για τη διάκριση της υπογραφής.
Χρησιμοποιήστε το SignatureId για να προσδιορίσετε τις επιλογές προεπισκόπησης.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Μοναδική τιμή για τη διάκριση της υπογραφής.
Χρησιμοποιήστε το SignatureId για να προσδιορίσετε τις επιλογές προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Επιλογές υπογραφής για τη δημιουργία προεπισκόπησης.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Επιλογές υπογραφής για τη δημιουργία προεπισκόπησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Λαμβάνει ή ορίζει τη μορφή των εικόνων προεπισκόπησης.
Η προεπιλεγμένη τιμή είναι PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Λαμβάνει ή ορίζει τη μορφή των εικόνων προεπισκόπησης.
Η προεπιλεγμένη τιμή είναι PNG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

