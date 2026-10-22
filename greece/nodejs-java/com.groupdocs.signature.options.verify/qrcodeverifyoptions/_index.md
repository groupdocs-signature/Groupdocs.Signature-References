---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Διατηρεί επιλογές για επαλήθευση υπογραφής QR-code εγγράφου."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Διατηρεί επιλογές για επαλήθευση υπογραφής QR-code εγγράφου.

--------------------

**Learn more**

 *  Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/
[Advanced usage of eVerification QR-code signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Δημιουργεί επιλογή επαλήθευσης QRCodeVerifyOptions για υπογραφές QR-Code. |
| [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Δημιουργεί επιλογή επαλήθευσης QRCodeVerifyOptions για υπογραφές QR-Code με κείμενο QR-Code προς επαλήθευση. |
| [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Δημιουργεί επιλογή επαλήθευσης QRCodeVerifyOptions για υπογραφές QR-Code με κείμενο και τύπο κωδικοποίησης QR-Code προς επαλήθευση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Αποκτά ή ορίζει την επαλήθευση τύπου QR-code. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Αποκτά ή ορίζει την επαλήθευση τύπου QR-code. |
| [getDataEncryption()](#getDataEncryption--) | Αποκτά ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων κειμένου υπογραφής QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Αποκτά ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων κειμένου υπογραφής QR-Code. |
| [toString()](#toString--) | Αντικαθιστά τη μετατροπή σε συμβολοσειρά. |
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Δημιουργεί επιλογή επαλήθευσης QRCodeVerifyOptions για υπογραφές QR-Code.

### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Δημιουργεί επιλογή επαλήθευσης QRCodeVerifyOptions για υπογραφές QR-Code με κείμενο QR-Code προς επαλήθευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο QR-code προς επαλήθευση |

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Δημιουργεί επιλογή επαλήθευσης QRCodeVerifyOptions για υπογραφές QR-Code με κείμενο και τύπο κωδικοποίησης QR-Code προς επαλήθευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο προς επαλήθευση |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Τύπος κωδικοποίησης |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Αποκτά ή ορίζει την επαλήθευση τύπου QR-code. Αυτή η ιδιότητα είναι προαιρετική.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Αποκτά ή ορίζει την επαλήθευση τύπου QR-code. Αυτή η ιδιότητα είναι προαιρετική.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Αποκτά ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων κειμένου υπογραφής QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Αποκτά ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων κειμένου υπογραφής QR-Code.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Αντικαθιστά τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
