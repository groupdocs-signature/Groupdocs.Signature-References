---
title: "SwissQR"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Klass för kodning och avkodning av text som är inbäddad i SwissQR‑koden."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Klass för kodning och avkodning av text som är inbäddad i SwissQR‑koden.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | Skapar en instans av SwissQR. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAmount()](#getAmount--) | Hämtar eller anger betalningsbeloppet. |
|
|  | [setAmount(double value)](#setAmount-double-) | Hämtar eller anger betalningsbeloppet. |
|
|  | [getCurrency()](#getCurrency--) | Hämtar eller anger betalningsvalutan. |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | Hämtar eller anger betalningsvalutan. |
|
|  | [getAccount()](#getAccount--) | Hämtar eller anger borgenärens kontonummer. |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | Hämtar eller anger borgenärens kontonummer. |
|
|  | [getCreditor()](#getCreditor--) | Hämtar eller anger borgenärens adress. |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Hämtar eller anger borgenärens adress. |
|
|  | [getReference()](#getReference--) | Hämtar eller anger borgenärens betalningsreferens. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Hämtar eller anger borgenärens betalningsreferens. |
|
|  | [getDebtor()](#getDebtor--) | Hämtar eller anger gäldenärens adress. |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Hämtar eller anger gäldenärens adress. |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | Hämtar eller anger det ytterligare ostrukturerade meddelandet. |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Hämtar eller anger det ytterligare ostrukturerade meddelandet. |
|
|  | [getBillInformation()](#getBillInformation--) | Hämtar eller anger den ytterligare strukturerade fakturainformationen. |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Hämtar eller anger den ytterligare strukturerade fakturainformationen. |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Skapar en instans av SwissQR.


### getAmount() {#getAmount--}
```
public final double getAmount()
```


Hämtar eller anger betalningsbeloppet.
Giltiga värden är mellan 0,01 och 999 999 999,99.
Värde: Betalningsbeloppet.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Hämtar eller anger betalningsbeloppet.
Giltiga värden är mellan 0,01 och 999 999 999,99.
Värde: Betalningsbeloppet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Hämtar eller anger betalningsvalutan.
Giltiga värden är "CHF" och "EUR".
Värde: Betalningsvalutan.


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Hämtar eller anger betalningsvalutan.
Giltiga värden är "CHF" och "EUR".
Värde: Betalningsvalutan.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Hämtar eller anger borgenärens kontonummer.
Kontonummer måste vara giltiga IBAN för en bank i Schweiz eller Liechtenstein.
Mellanslag är tillåtna i kontonumret.
Värde: Borgenärens kontonummer.


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Hämtar eller anger borgenärens kontonummer.
Kontonummer måste vara giltiga IBAN för en bank i Schweiz eller Liechtenstein.
Mellanslag är tillåtna i kontonumret.
Värde: Borgenärens kontonummer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Hämtar eller anger borgenärens adress.
Värde: Borgenärens adress.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Hämtar eller anger borgenärens adress.
Värde: Borgenärens adress.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Hämtar eller anger borgenärens betalningsreferens.
Referensen är obligatorisk för SwissQR-IBAN, d.v.s. IBAN i intervallet CHxx30000xxxxxx
till CHxx31999xxxxx.
Om angiven måste referensen vara antingen en giltig SwissQR-referens (motsvarande
till ISR-referensform) eller en giltig borgenärsreferens enligt ISO 11649 ("RFxxxx").
Båda kan innehålla mellanslag för formatering.
Värde: Borgenärens betalningsreferens.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Hämtar eller anger borgenärens betalningsreferens.
Referensen är obligatorisk för SwissQR-IBAN, d.v.s. IBAN i intervallet CHxx30000xxxxxx
till CHxx31999xxxxx.
Om angiven måste referensen vara antingen en giltig SwissQR-referens (motsvarande
till ISR-referensform) eller en giltig borgenärsreferens enligt ISO 11649 ("RFxxxx").
Båda kan innehålla mellanslag för formatering.
Värde: Borgenärens betalningsreferens.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Hämtar eller anger gäldenärens adress.
Gäldenären är valfri. Om den utelämnas kan både sätta detta fält till null eller
sätta en adress med alla null- eller tomma värden vara okej.
Värde: Gäldenärens adress.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Hämtar eller anger gäldenärens adress.
Gäldenären är valfri. Om den utelämnas kan både sätta detta fält till null eller
sätta en adress med alla null- eller tomma värden vara okej.
Värde: Gäldenärens adress.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Hämtar eller anger det ytterligare ostrukturerade meddelandet.
Värde: Det ostrukturerade meddelandet.


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Hämtar eller anger det ytterligare ostrukturerade meddelandet.
Värde: Det ostrukturerade meddelandet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Hämtar eller anger den ytterligare strukturerade fakturainformationen.
Värde: Den strukturerade fakturainformationen.


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Hämtar eller anger den ytterligare strukturerade fakturainformationen.
Värde: Den strukturerade fakturainformationen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

