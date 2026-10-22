---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αναπαριστά τις επιλογές επαλήθευσης Barcode."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Αναπαριστά τις επιλογές επαλήθευσης Barcode.

--------------------

 **Learn more**  **Learn more**

 *  Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ][How to eVerification Barcode signatures in a document]
 *  Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings


[How to eVerification Barcode signatures in a document]: https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Δημιουργεί προεπιλεγμένη επιλογή επαλήθευσης για υπογραφή Barcode. |
| [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Δημιουργεί προεπιλεγμένη επιλογή επαλήθευσης με κείμενο επαλήθευσης |
| [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Δημιουργεί προεπιλεγμένη επιλογή επαλήθευσης με επαλήθευση τύπου Barcode |
| [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Δημιουργεί προεπιλεγμένη επιλογή επαλήθευσης με επαλήθευση τύπου Barcode και κείμενο |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Αποκτά ή ορίζει την επαλήθευση τύπου Barcode. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Αποκτά ή ορίζει την επαλήθευση τύπου Barcode. |
| [toString()](#toString--) | Αντικαθιστά τη μετατροπή σε συμβολοσειρά. |
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Δημιουργεί προεπιλεγμένη επιλογή επαλήθευσης για υπογραφή Barcode.

### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Δημιουργεί προεπιλεγμένη επιλογή επαλήθευσης με κείμενο επαλήθευσης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο Barcode προς επαλήθευση |

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Δημιουργεί προεπιλεγμένη επιλογή επαλήθευσης με επαλήθευση τύπου Barcode

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Επαλήθευση τύπου Barcode |

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Δημιουργεί προεπιλεγμένη επιλογή επαλήθευσης με επαλήθευση τύπου Barcode και κείμενο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο Barcode προς επαλήθευση |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Επαλήθευση τύπου Barcode |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Αποκτά ή ορίζει την επαλήθευση τύπου Barcode.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Αποκτά ή ορίζει την επαλήθευση τύπου Barcode.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Αντικαθιστά τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
