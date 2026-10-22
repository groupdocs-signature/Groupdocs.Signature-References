---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Descrive l'aspetto della linea della firma per la firma digitale."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Descrive l'aspetto della linea di firma per la firma digitale. Una linea di firma può essere applicata a una sola firma digitale. La linea di firma è sempre nella prima pagina. Questa funzionalità può essere utile per i formati di file .docx, .doc, .odt e .xlsx.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Crea l'oggetto di aspetto della linea di firma. |
| [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Crea l'aspetto della linea di firma con i valori specificati (firmatario, titolo, email). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSigner()](#getSigner--) | Ottiene o imposta il nome del firmatario per la linea di firma. |
| [setSigner(String value)](#setSigner-java.lang.String-) | Ottiene o imposta il nome del firmatario per la linea di firma. |
| [getTitle()](#getTitle--) | Ottiene o imposta un titolo per la linea di firma. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Ottiene o imposta un titolo per la linea di firma. |
| [getEmail()](#getEmail--) | Ottiene o imposta un'email che verrà visualizzata nella linea di firma. |
| [setEmail(String value)](#setEmail-java.lang.String-) | Ottiene o imposta un'email che verrà visualizzata nella linea di firma. |
| [toString()](#toString--) | Sovrascrive la conversione di stringa. |
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Crea l'oggetto di aspetto della linea di firma.

### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Crea l'aspetto della linea di firma con i valori specificati (firmatario, titolo, email).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firmatario | java.lang.String | Nome del firmatario. |
| titolo | java.lang.String | Titolo della firma. |
| email | java.lang.String | Email dell'autore. |

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Ottiene o imposta il nome del firmatario per la linea di firma.

**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Ottiene o imposta il nome del firmatario per la linea di firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Ottiene o imposta un titolo per la linea di firma.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Ottiene o imposta un titolo per la linea di firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Ottiene o imposta un'email che verrà visualizzata nella linea di firma.

**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Ottiene o imposta un'email che verrà visualizzata nella linea di firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione di stringa.

**Returns:**
java.lang.String -
