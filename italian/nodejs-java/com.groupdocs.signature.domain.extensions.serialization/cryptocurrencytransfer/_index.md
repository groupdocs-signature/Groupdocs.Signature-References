---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta il destinatario o il trasferimento di criptovaluta per il QR-Code."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

Rappresenta il trasferimento di criptovaluta (destinatario o trasferimento) per QR-Code.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Ottiene o imposta uno dei tipi di criptovaluta supportati. |
| [setType(int value)](#setType-int-) | Ottiene o imposta uno dei tipi di criptovaluta supportati. |
| [getAmount()](#getAmount--) | Ottiene o imposta l'importo del trasferimento. |
| [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Ottiene o imposta l'importo del trasferimento. |
| [getAddress()](#getAddress--) | Ottiene o imposta l'indirizzo pubblico della criptovaluta. |
| [setAddress(String value)](#setAddress-java.lang.String-) | Ottiene o imposta l'indirizzo pubblico della criptovaluta. |
| [getMessage()](#getMessage--) | Ottiene o imposta il messaggio opzionale del trasferimento. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Ottiene o imposta il messaggio opzionale del trasferimento. |
| [getCustomType()](#getCustomType--) | Ottiene o imposta il messaggio opzionale del trasferimento. |
| [setCustomType(String value)](#setCustomType-java.lang.String-) | Ottiene o imposta il messaggio opzionale del trasferimento. |
| [equals(Object obj)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà del trasferimento di criptovaluta. |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Ottiene o imposta uno dei tipi di criptovaluta supportati.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Ottiene o imposta uno dei tipi di criptovaluta supportati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Ottiene o imposta l'importo del trasferimento.

**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Ottiene o imposta l'importo del trasferimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Ottiene o imposta l'indirizzo pubblico della criptovaluta.

**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Ottiene o imposta l'indirizzo pubblico della criptovaluta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Ottiene o imposta il messaggio opzionale del trasferimento.

**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Ottiene o imposta il messaggio opzionale del trasferimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


Ottiene o imposta il messaggio opzionale del trasferimento.

**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


Ottiene o imposta il messaggio opzionale del trasferimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Sovrascrive il metodo Equals per confrontare le proprietà del trasferimento di criptovaluta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Oggetto di trasferimento di criptovaluta con cui confrontare. |

**Returns:**
boolean - Restituisce true se l'oggetto di trasferimento di criptovaluta passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode

**Returns:**
int - Codice hash del trasferimento di criptovaluta.
