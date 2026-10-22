---
title: "CertificateVerifyOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Mantiene le opzioni per verificare i documenti certificati."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Mantiene le opzioni per verificare i documenti certificati.

--------------------

 **Learn more** 

 *  
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Inizializza una nuova istanza di TextVerifyOptions con i valori predefiniti. |
| [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Inizializza una nuova istanza di CertificateVerifyOptions con il soggetto da verificare. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIssuer()](#getIssuer--) | Specifica l'emittente del certificato se deve essere verificato. |
| [setIssuer(String value)](#setIssuer-java.lang.String-) | Specifica l'emittente del certificato se deve essere verificato. |
| [getSerialNumber()](#getSerialNumber--) | Specifica il numero di serie del certificato se deve essere verificato. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Specifica il numero di serie del certificato se deve essere verificato. |
| [getSubject()](#getSubject--) | Specifica il soggetto del certificato se deve essere verificato. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Specifica il soggetto del certificato se deve essere verificato. |
| [getThumbprint()](#getThumbprint--) | Specifica l'impronta digitale del certificato se deve essere verificata. |
| [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Specifica l'impronta digitale del certificato se deve essere verificata. |
| [getMatchType()](#getMatchType--) | Ottiene o imposta la verifica del tipo di corrispondenza del testo. |
| [setMatchType(int value)](#setMatchType-int-) | Ottiene o imposta la verifica del tipo di corrispondenza del testo. |
| [getExpired()](#getExpired--) | Indica se il certificato è scaduto a causa del risultato della convalida. |
| [setExpired(boolean value)](#setExpired-boolean-) | Indica se il certificato è scaduto a causa del risultato della convalida. |
| [getPerformChainValidation()](#getPerformChainValidation--) | Ottieni o imposta se il processo di verifica deve fornire la convalida della catena X.509 utilizzando la politica di convalida di base. |
| [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Ottieni o imposta se il processo di verifica deve fornire la convalida della catena X.509 utilizzando la politica di convalida di base. |
| [toString()](#toString--) | Sovrascrive la conversione in stringa. |
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Inizializza una nuova istanza di TextVerifyOptions con i valori predefiniti.

### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Inizializza una nuova istanza di CertificateVerifyOptions con il soggetto da verificare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oggetto | java.lang.String | Soggetto da verificare |

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Specifica l'emittente del certificato se deve essere verificato.

**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Specifica l'emittente del certificato se deve essere verificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Specifica il numero di serie del certificato se deve essere verificato.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Specifica il numero di serie del certificato se deve essere verificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Specifica il soggetto del certificato se deve essere verificato.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Specifica il soggetto del certificato se deve essere verificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Specifica l'impronta digitale del certificato se deve essere verificata.

**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Specifica l'impronta digitale del certificato se deve essere verificata.

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

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Indica se il certificato è scaduto a causa del risultato della convalida. La proprietà è di sola lettura.

**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Indica se il certificato è scaduto a causa del risultato della convalida. La proprietà è di sola lettura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Ottieni o imposta se il processo di verifica deve fornire la convalida della catena X.509 utilizzando la politica di convalida di base. Per impostazione predefinita questo valore è true.

**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Ottieni o imposta se il processo di verifica deve fornire la convalida della catena X.509 utilizzando la politica di convalida di base. Per impostazione predefinita questo valore è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione in stringa.

**Returns:**
java.lang.String -
