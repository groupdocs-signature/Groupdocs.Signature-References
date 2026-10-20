---
title: "EPC"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar European Payments Council Quick Response Code."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Representerar European Payments Council Quick Response Code.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [EPC()](#EPC--) | Instansierar ett nytt EPC-objekt. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Hämtar eller anger förmånstagarens namn. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger förmånstagarens namn. |
|
|  | [getBIC()](#getBIC--) | Hämtar eller anger förmånstagarens BIC med upp till 11 tecken. |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | Hämtar eller anger förmånstagarens BIC med upp till 11 tecken. |
|
|  | [getIBAN()](#getIBAN--) | Hämtar eller anger förmånstagarens konto (IBAN). |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | Hämtar eller anger förmånstagarens konto (IBAN). |
|
|  | [getAmount()](#getAmount--) | Hämtar eller anger belopp. |
|
|  | [setAmount(double value)](#setAmount-double-) | Hämtar eller anger belopp. |
|
|  | [getCode()](#getCode--) | Hämtar eller anger affärskod med upp till 4 tecken. |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | Hämtar eller anger affärskod med upp till 4 tecken. |
|
|  | [getReference()](#getReference--) | Hämtar eller anger betalningsreferens (maximalt 35 tecken). |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Hämtar eller anger betalningsreferens (maximalt 35 tecken). |
|
|  | [getRemittance()](#getRemittance--) | Hämtar eller anger betalningsinformation (maximalt 140 tecken). |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | Hämtar eller anger betalningsinformation (maximalt 140 tecken). |
|
|  | [getInformation()](#getInformation--) | Hämtar eller anger ledtrådsinformation. |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | Hämtar eller anger ledtrådsinformation. |
|
|  | [getVersion()](#getVersion--) | EPC / SEPA QR-Code versionimplementering. |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | EPC / SEPA QR-Code versionimplementering. |
|
|  | [getCharset()](#getCharset--) | EPC / SEPA QR-Code teckenuppsättningsimplementering. |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | EPC / SEPA QR-Code teckenuppsättningsimplementering. |
|
|  | [getIdentification()](#getIdentification--) | EPC / SEPA QR-Code identifiering. |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | EPC / SEPA QR-Code identifiering. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra EPC-egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
### EPC() {#EPC--}
```
public EPC()
```


Instansierar ett nytt EPC-objekt.


### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger mottagarens namn. Maxlängden är 70 tecken.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Hämtar eller anger mottagarens namn. Maxlängden är 70 tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Hämtar eller anger förmånstagarens BIC med upp till 11 tecken.


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Hämtar eller anger förmånstagarens BIC med upp till 11 tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Hämtar eller anger mottagarens konto (IBAN). IBAN består av upp till 34 alfanumeriska tecken.


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Hämtar eller anger mottagarens konto (IBAN). IBAN består av upp till 34 alfanumeriska tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Hämtar eller anger belopp.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Hämtar eller anger belopp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Hämtar eller anger affärskod med upp till 4 tecken.


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Hämtar eller anger affärskod med upp till 4 tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Hämtar eller anger betalningsreferens (maximalt 35 tecken). Detta fält och fältet för betalningsinformation är ömsesidigt uteslutande.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Hämtar eller anger betalningsreferens (maximalt 35 tecken). Detta fält och fältet för betalningsinformation är ömsesidigt uteslutande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Hämtar eller anger betalningsinformation (maximalt 140 tecken). Detta fält och fältet för betalningsreferens är ömsesidigt uteslutande.


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Hämtar eller anger betalningsinformation (maximalt 140 tecken). Detta fält och fältet för betalningsreferens är ömsesidigt uteslutande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Hämtar eller anger tipsinformation. Max 70 tecken.


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Hämtar eller anger tipsinformation. Max 70 tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


EPC / SEPA QR-Code versionimplementering. Standardvärdet är 002.


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


EPC / SEPA QR-Code versionimplementering. Standardvärdet är 002.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


EPC / SEPA QR-Code teckenuppsättningsimplementering. Standardvärdet är 1


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


EPC / SEPA QR-Code teckenuppsättningsimplementering. Standardvärdet är 1


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


EPC / SEPA QR-Code identifiering. Standardvärdet är SCT


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


EPC / SEPA QR-Code identifiering. Standardvärdet är SCT


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Skriver över Equals-metoden för att jämföra EPC-egenskaper


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | källa | java.lang.Object | EPC-objekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda adressobjektet har samma typ och alla dess egenskaper är lika med den här instansens egenskaper.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - Email hashkod

