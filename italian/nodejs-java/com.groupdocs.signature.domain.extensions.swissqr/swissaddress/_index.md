---
title: "SwissAddress"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta l'indirizzo del creditore o del debitore."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Rappresenta l'indirizzo del creditore o del debitore. È possibile impostare via, numero civico, codice postale e città (tipo di indirizzo strutturato) oppure la riga indirizzo 1 e 2 (tipo di elementi di indirizzo combinati).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Ottiene o imposta il nome, sia il nome e cognome di una persona fisica sia la ragione sociale di una persona giuridica. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome, sia il nome e cognome di una persona fisica sia la ragione sociale di una persona giuridica. |
| [getAddressLine1()](#getAddressLine1--) | Ottiene o imposta la riga indirizzo 1. |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Ottiene o imposta la riga indirizzo 1. |
| [getAddressLine2()](#getAddressLine2--) | Ottiene o imposta la riga indirizzo 2. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Ottiene o imposta la riga indirizzo 2. |
| [getStreet()](#getStreet--) | Ottiene o imposta la via. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Ottiene o imposta la via. |
| [getHouseNo()](#getHouseNo--) | Ottiene o imposta il numero civico. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Ottiene o imposta il numero civico. |
| [getPostalCode()](#getPostalCode--) | Ottiene o imposta il codice postale. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Ottiene o imposta il codice postale. |
| [getTown()](#getTown--) | Ottiene o imposta la città o il comune. |
| [setTown(String value)](#setTown-java.lang.String-) | Ottiene o imposta la città o il comune. |
| [getCountryCode()](#getCountryCode--) | Ottiene o imposta il codice paese ISO a due lettere. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Ottiene o imposta il codice paese ISO a due lettere. |
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Ottiene o imposta il nome, sia il nome e cognome di una persona fisica sia la ragione sociale di una persona giuridica.

Valore: Il nome.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ottiene o imposta il nome, sia il nome e cognome di una persona fisica sia la ragione sociale di una persona giuridica.

Valore: Il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Ottiene o imposta la prima riga dell'indirizzo. La prima riga dell'indirizzo contiene il nome della via, il numero civico o la casella postale. Questo campo è usato solo per indirizzi con elementi combinati ed è opzionale.

Valore: La prima riga dell'indirizzo.

**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Ottiene o imposta la prima riga dell'indirizzo. La prima riga dell'indirizzo contiene il nome della via, il numero civico o la casella postale. Questo campo è usato solo per indirizzi con elementi combinati ed è opzionale.

Valore: La prima riga dell'indirizzo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Ottiene o imposta la seconda riga dell'indirizzo. La seconda riga dell'indirizzo contiene il codice postale e la città. Questo campo è usato solo per indirizzi con elementi combinati. Per questo tipo, è obbligatorio.

Valore: La seconda riga dell'indirizzo.

**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Ottiene o imposta la seconda riga dell'indirizzo. La seconda riga dell'indirizzo contiene il codice postale e la città. Questo campo è usato solo per indirizzi con elementi combinati. Per questo tipo, è obbligatorio.

Valore: La seconda riga dell'indirizzo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Ottiene o imposta la via. La via deve essere specificata senza numero civico. Questo campo è usato solo per indirizzi strutturati ed è opzionale.

Valore: La via.

**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Ottiene o imposta la via. La via deve essere specificata senza numero civico. Questo campo è usato solo per indirizzi strutturati ed è opzionale.

Valore: La via.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Ottiene o imposta il numero civico. Questo campo è usato solo per indirizzi strutturati ed è opzionale.

Valore: Il numero civico.

**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Ottiene o imposta il numero civico. Questo campo è usato solo per indirizzi strutturati ed è opzionale.

Valore: Il numero civico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Ottiene o imposta il codice postale. Questo campo è usato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

Valore: Il codice postale.

**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Ottiene o imposta il codice postale. Questo campo è usato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

Valore: Il codice postale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Ottiene o imposta la città o il comune. Questo campo è usato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

Valore: La città o il comune.

**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Ottiene o imposta la città o il comune. Questo campo è usato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

Valore: La città o il comune.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Ottiene o imposta il codice paese ISO a due lettere. Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori null o vuoti.

Valore: Il codice ISO del paese.

**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Ottiene o imposta il codice paese ISO a due lettere. Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori null o vuoti.

Valore: Il codice ISO del paese.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

