---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di verifica del codice a barre."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Rappresenta le opzioni di verifica del codice a barre.

--------------------

 **Learn more**  **Learn more**

 *  Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ][How to eVerification Barcode signatures in a document]
 *  Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings


[How to eVerification Barcode signatures in a document]: https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Crea l'opzione di verifica predefinita per la firma Barcode. |
| [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Crea l'opzione di verifica predefinita con testo di verifica |
| [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Crea l'opzione di verifica predefinita con verifica del tipo Barcode |
| [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Crea l'opzione di verifica predefinita con verifica del tipo Barcode e testo |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Ottiene o imposta la verifica del tipo Barcode. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Ottiene o imposta la verifica del tipo Barcode. |
| [toString()](#toString--) | Sovrascrive la conversione in stringa. |
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Crea l'opzione di verifica predefinita per la firma Barcode.

### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Crea l'opzione di verifica predefinita con testo di verifica

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Testo Barcode da verificare |

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Crea l'opzione di verifica predefinita con verifica del tipo Barcode

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Verifica del tipo Barcode |

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Crea l'opzione di verifica predefinita con verifica del tipo Barcode e testo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Testo Barcode da verificare |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Verifica del tipo Barcode |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Ottiene o imposta la verifica del tipo Barcode.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Ottiene o imposta la verifica del tipo Barcode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione in stringa.

**Returns:**
java.lang.String -
