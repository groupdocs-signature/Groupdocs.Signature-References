---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Mantiene le opzioni per verificare la firma di testo del documento."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Mantiene le opzioni per verificare la firma di testo del documento.

--------------------

**Learn more**

 *  Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/
[Advanced usage of eVerification Barcode signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-text-signatures/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextVerifyOptions()](#TextVerifyOptions--) | Inizializza una nuova istanza di TextVerifyOptions con i valori predefiniti. |
| [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Inizializza una nuova istanza di TextVerifyOptions con il testo di verifica. |
| [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Inizializza una nuova istanza di TextVerifyOptions con la proprietà Text da verificare e l'implementazione della firma. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Specifica il testo della firma se deve essere verificato. |
| [setText(String value)](#setText-java.lang.String-) | Specifica il testo della firma se deve essere verificato. |
| [getMatchType()](#getMatchType--) | Ottiene o imposta la verifica del tipo di corrispondenza del testo. |
| [setMatchType(int value)](#setMatchType-int-) | Ottiene o imposta la verifica del tipo di corrispondenza del testo. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Tipo di firma da verificare. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Tipo di firma da verificare. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Ottiene o imposta il titolo del campo modulo da verificare. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Ottiene o imposta il titolo del campo modulo da verificare. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Ottiene o imposta il tipo di campo modulo da verificare. |
| [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Ottiene o imposta il tipo di campo modulo da verificare. |
| [getSignatureID()](#getSignatureID--) | Specifica un ID della firma di testo maggiore di zero se deve essere verificato. |
| [setSignatureID(int value)](#setSignatureID-int-) | Specifica un ID della firma di testo maggiore di zero se deve essere verificato. |
| [toString()](#toString--) | Sovrascrive la conversione in stringa. |
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Inizializza una nuova istanza di TextVerifyOptions con i valori predefiniti.

### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Inizializza una nuova istanza di TextVerifyOptions con il testo di verifica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Testo da verificare |

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Inizializza una nuova istanza di TextVerifyOptions con la proprietà Text da verificare e l'implementazione della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Testo da verificare. |
| implementazione | int | Tipo di implementazione della firma. |

### getText() {#getText--}
```
public final String getText()
```


Specifica il testo della firma se deve essere verificato.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specifica il testo della firma se deve essere verificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Ottiene o imposta la verifica del tipo di corrispondenza del testo.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Ottiene o imposta la verifica del tipo di corrispondenza del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Tipo di firma da verificare.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Tipo di firma da verificare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Ottiene o imposta il titolo del campo modulo da verificare. Se questa proprietà è impostata, il testo verrà trovato solo nei campi modulo di testo.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Ottiene o imposta il titolo del campo modulo da verificare. Se questa proprietà è impostata, il testo verrà trovato solo nei campi modulo di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Ottiene o imposta il tipo di campo modulo da verificare. Se questa proprietà è impostata, il testo verrà trovato solo nei campi modulo di testo.

**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Ottiene o imposta il tipo di campo modulo da verificare. Se questa proprietà è impostata, il testo verrà trovato solo nei campi modulo di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Specifica un ID della firma di testo maggiore di zero se deve essere verificato. Questa proprietà è supportata solo per i documenti PDF

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Specifica un ID della firma di testo maggiore di zero se deve essere verificato. Questa proprietà è supportata solo per i documenti PDF

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione in stringa.

**Returns:**
java.lang.String -
