---
title: "EPC"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt de European Payments Council Quick Response Code voor."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Stelt de European Payments Council Quick Response Code voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EPC()](#EPC--) | Instantieert een nieuw EPC-object. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Haalt op of stelt de naam van de begunstigde in. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Haalt op of stelt de naam van de begunstigde in. |
|
|  | [getBIC()](#getBIC--) | Haalt op of stelt de BIC van de begunstigde in met een maximale lengte van 11 tekens. |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | Haalt op of stelt de BIC van de begunstigde in met een maximale lengte van 11 tekens. |
|
|  | [getIBAN()](#getIBAN--) | Haalt op of stelt de rekening van de begunstigde (IBAN) in. |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | Haalt op of stelt de rekening van de begunstigde (IBAN) in. |
|
|  | [getAmount()](#getAmount--) | Haalt op of stelt het bedrag in. |
|
|  | [setAmount(double value)](#setAmount-double-) | Haalt op of stelt het bedrag in. |
|
|  | [getCode()](#getCode--) | Haalt op of stelt de bedrijfscode in met maximaal 4 tekens. |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | Haalt op of stelt de bedrijfscode in met maximaal 4 tekens. |
|
|  | [getReference()](#getReference--) | Haalt op of stelt de betalingsreferentie in (maximaal 35 tekens). |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Haalt op of stelt de betalingsreferentie in (maximaal 35 tekens). |
|
|  | [getRemittance()](#getRemittance--) | Haalt op of stelt de overboekingsinformatie in (maximaal 140 tekens). |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | Haalt op of stelt de overboekingsinformatie in (maximaal 140 tekens). |
|
|  | [getInformation()](#getInformation--) | Haalt op of stelt hintinformatie in. |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | Haalt op of stelt hintinformatie in. |
|
|  | [getVersion()](#getVersion--) | Implementatie van EPC / SEPA QR-Code versie. |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | Implementatie van EPC / SEPA QR-Code versie. |
|
|  | [getCharset()](#getCharset--) | Implementatie van EPC / SEPA QR-Code tekenset. |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | Implementatie van EPC / SEPA QR-Code tekenset. |
|
|  | [getIdentification()](#getIdentification--) | Identificatie van EPC / SEPA QR-Code. |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | Identificatie van EPC / SEPA QR-Code. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om EPC-eigenschappen te vergelijken. |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
### EPC() {#EPC--}
```
public EPC()
```


Instantieert een nieuw EPC-object.


### getName() {#getName--}
```
public final String getName()
```


Haalt op of stelt de naam van de begunstigde in. Maximale lengte is 70 tekens.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Haalt op of stelt de naam van de begunstigde in. Maximale lengte is 70 tekens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Haalt op of stelt de BIC van de begunstigde in met een maximale lengte van 11 tekens.


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Haalt op of stelt de BIC van de begunstigde in met een maximale lengte van 11 tekens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Haalt op of stelt de rekening van de begunstigde in (IBAN). De IBAN bestaat uit maximaal 34 alfanumerieke tekens.


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Haalt op of stelt de rekening van de begunstigde in (IBAN). De IBAN bestaat uit maximaal 34 alfanumerieke tekens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Haalt op of stelt het bedrag in.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Haalt op of stelt het bedrag in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Haalt op of stelt de bedrijfscode in met maximaal 4 tekens.


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Haalt op of stelt de bedrijfscode in met maximaal 4 tekens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Haalt op of stelt de betalingsreferentie in (maximaal 35 tekens). Dit veld en het veld Remittance Information zijn wederzijds exclusief.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Haalt op of stelt de betalingsreferentie in (maximaal 35 tekens). Dit veld en het veld Remittance Information zijn wederzijds exclusief.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Haalt op of stelt Remittance Information in (maximaal 140 tekens). Dit veld en het veld Payment Reference zijn wederzijds exclusief.


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Haalt op of stelt Remittance Information in (maximaal 140 tekens). Dit veld en het veld Payment Reference zijn wederzijds exclusief.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Haalt op of stelt hint-informatie in. Maximaal 70 tekens.


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Haalt op of stelt hint-informatie in. Maximaal 70 tekens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Implementatie van EPC / SEPA QR-Code versie. Standaard wordt deze waarde ingesteld op 002.


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Implementatie van EPC / SEPA QR-Code versie. Standaard wordt deze waarde ingesteld op 002.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


Implementatie van EPC / SEPA QR-Code tekenset. Standaard wordt deze waarde ingesteld op 1.


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


Implementatie van EPC / SEPA QR-Code tekenset. Standaard wordt deze waarde ingesteld op 1.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


Identificatie van EPC / SEPA QR-Code. Standaard wordt deze waarde ingesteld op SCT.


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


Identificatie van EPC / SEPA QR-Code. Standaard wordt deze waarde ingesteld op SCT.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Overschrijft de Equals-methode om EPC-eigenschappen te vergelijken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bron | java.lang.Object | EPC-object om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als het meegegeven adresobject hetzelfde type heeft en al zijn eigenschappen gelijk zijn aan de eigenschappen van deze instantie.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft de GetHashCode‑methode


**Returns:**
int - E-mail-hashcode

