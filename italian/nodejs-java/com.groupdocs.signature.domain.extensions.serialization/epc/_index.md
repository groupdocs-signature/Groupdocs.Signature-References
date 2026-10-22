---
title: "EPC"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta il Quick Response Code del European Payments Council."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Rappresenta il Quick Response Code del European Payments Council.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EPC()](#EPC--) | Istanzia un nuovo oggetto EPC. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Ottiene o imposta il nome del beneficiario. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome del beneficiario. |
| [getBIC()](#getBIC--) | Ottiene o imposta il BIC del beneficiario con una lunghezza massima di 11 caratteri. |
| [setBIC(String value)](#setBIC-java.lang.String-) | Ottiene o imposta il BIC del beneficiario con una lunghezza massima di 11 caratteri. |
| [getIBAN()](#getIBAN--) | Ottiene o imposta il conto del beneficiario (IBAN). |
| [setIBAN(String value)](#setIBAN-java.lang.String-) | Ottiene o imposta il conto del beneficiario (IBAN). |
| [getAmount()](#getAmount--) | Ottiene o imposta l'importo. |
| [setAmount(double value)](#setAmount-double-) | Ottiene o imposta l'importo. |
| [getCode()](#getCode--) | Ottiene o imposta il codice aziendale fino a 4 caratteri. |
| [setCode(String value)](#setCode-java.lang.String-) | Ottiene o imposta il codice aziendale fino a 4 caratteri. |
| [getReference()](#getReference--) | Ottiene o imposta il riferimento di pagamento (massimo 35 caratteri). |
| [setReference(String value)](#setReference-java.lang.String-) | Ottiene o imposta il riferimento di pagamento (massimo 35 caratteri). |
| [getRemittance()](#getRemittance--) | Ottiene o imposta le informazioni di rimessa (massimo 140 caratteri). |
| [setRemittance(String value)](#setRemittance-java.lang.String-) | Ottiene o imposta le informazioni di rimessa (massimo 140 caratteri). |
| [getInformation()](#getInformation--) | Ottiene o imposta le informazioni di suggerimento. |
| [setInformation(String value)](#setInformation-java.lang.String-) | Ottiene o imposta le informazioni di suggerimento. |
| [getVersion()](#getVersion--) | Implementazione della versione EPC / SEPA QR-Code. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Implementazione della versione EPC / SEPA QR-Code. |
| [getCharset()](#getCharset--) | Implementazione del set di caratteri EPC / SEPA QR-Code. |
| [setCharset(String value)](#setCharset-java.lang.String-) | Implementazione del set di caratteri EPC / SEPA QR-Code. |
| [getIdentification()](#getIdentification--) | Identificazione EPC / SEPA QR-Code. |
| [setIdentification(String value)](#setIdentification-java.lang.String-) | Identificazione EPC / SEPA QR-Code. |
| [equals(Object source)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà EPC. |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
### EPC() {#EPC--}
```
public EPC()
```


Istanzia un nuovo oggetto EPC.

### getName() {#getName--}
```
public final String getName()
```


Ottiene o imposta il nome del beneficiario. La lunghezza massima è 70 caratteri.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ottiene o imposta il nome del beneficiario. La lunghezza massima è 70 caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Ottiene o imposta il BIC del beneficiario con una lunghezza massima di 11 caratteri.

**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Ottiene o imposta il BIC del beneficiario con una lunghezza massima di 11 caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Ottiene o imposta il conto del beneficiario (IBAN). L'IBAN è composto da un massimo di 34 caratteri alfanumerici.

**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Ottiene o imposta il conto del beneficiario (IBAN). L'IBAN è composto da un massimo di 34 caratteri alfanumerici.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Ottiene o imposta l'importo.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Ottiene o imposta l'importo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Ottiene o imposta il codice aziendale fino a 4 caratteri.

**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Ottiene o imposta il codice aziendale fino a 4 caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Ottiene o imposta il riferimento di pagamento (massimo 35 caratteri). Questo campo e il campo delle informazioni di rimessa sono mutualmente esclusivi.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Ottiene o imposta il riferimento di pagamento (massimo 35 caratteri). Questo campo e il campo delle informazioni di rimessa sono mutualmente esclusivi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Ottiene o imposta le informazioni di rimessa (massimo 140 caratteri). Questo campo e il campo del riferimento di pagamento sono mutualmente esclusivi.

**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Ottiene o imposta le informazioni di rimessa (massimo 140 caratteri). Questo campo e il campo del riferimento di pagamento sono mutualmente esclusivi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Ottiene o imposta le informazioni di suggerimento. Massimo 70 caratteri.

**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Ottiene o imposta le informazioni di suggerimento. Massimo 70 caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Implementazione della versione EPC / SEPA QR-Code. Per impostazione predefinita questo valore è impostato a 002.

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Implementazione della versione EPC / SEPA QR-Code. Per impostazione predefinita questo valore è impostato a 002.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


Implementazione del set di caratteri EPC / SEPA QR-Code. Per impostazione predefinita questo valore è impostato a 1

**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


Implementazione del set di caratteri EPC / SEPA QR-Code. Per impostazione predefinita questo valore è impostato a 1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


Identificazione EPC / SEPA QR-Code. Per impostazione predefinita questo valore è impostato a SCT

**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


Identificazione EPC / SEPA QR-Code. Per impostazione predefinita questo valore è impostato a SCT

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Sovrascrive il metodo Equals per confrontare le proprietà EPC.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origine | java.lang.Object | Oggetto EPC con cui confrontare. |

**Returns:**
boolean - Restituisce true se l'oggetto indirizzo passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode

**Returns:**
int - Codice hash dell'Email.
