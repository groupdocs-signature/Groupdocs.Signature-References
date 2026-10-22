---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de vérification du code-barres."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Représente les options de vérification du code-barres.

--------------------

 **Learn more**  **Learn more**

 *  Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ][How to eVerification Barcode signatures in a document]
 *  Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings


[How to eVerification Barcode signatures in a document]: https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Crée l'option de vérification par défaut pour la signature de code-barres. |
| [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Crée l'option de vérification par défaut avec le texte de vérification |
| [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Crée l'option de vérification par défaut avec la vérification du type de code-barres |
| [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Crée l'option de vérification par défaut avec la vérification du type de code-barres et le texte |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Obtient ou définit la vérification du type de code-barres. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Obtient ou définit la vérification du type de code-barres. |
| [toString()](#toString--) | Surcharge la conversion en chaîne. |
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Crée l'option de vérification par défaut pour la signature de code-barres.

### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Crée l'option de vérification par défaut avec le texte de vérification

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Texte du code-barres à vérifier |

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Crée l'option de vérification par défaut avec la vérification du type de code-barres

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Vérification du type de code-barres |

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Crée l'option de vérification par défaut avec la vérification du type de code-barres et le texte

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Texte du code-barres à vérifier |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Vérification du type de code-barres |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Obtient ou définit la vérification du type de code-barres.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Obtient ou définit la vérification du type de code-barres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Surcharge la conversion en chaîne.

**Returns:**
java.lang.String -
