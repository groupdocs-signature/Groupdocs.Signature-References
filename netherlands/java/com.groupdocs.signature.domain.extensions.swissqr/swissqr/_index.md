---
title: "SwissQR"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die in de SwissQR‑code is ingebed."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Klasse voor het coderen en decoderen van de tekst die in de SwissQR‑code is ingebed.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | Maakt een instantie van SwissQR. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAmount()](#getAmount--) | Haalt op of stelt het betalingsbedrag in. |
|
|  | [setAmount(double value)](#setAmount-double-) | Haalt op of stelt het betalingsbedrag in. |
|
|  | [getCurrency()](#getCurrency--) | Haalt op of stelt de betaalvaluta in. |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | Haalt op of stelt de betaalvaluta in. |
|
|  | [getAccount()](#getAccount--) | Haalt op of stelt het rekeningnummer van de crediteur in. |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | Haalt op of stelt het rekeningnummer van de crediteur in. |
|
|  | [getCreditor()](#getCreditor--) | Haalt op of stelt het crediteuradres in. |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Haalt op of stelt het crediteuradres in. |
|
|  | [getReference()](#getReference--) | Haalt of stelt de crediteur betalingsreferentie in. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Haalt of stelt de crediteur betalingsreferentie in. |
|
|  | [getDebtor()](#getDebtor--) | Haalt of stelt het debiteuradres in. |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Haalt of stelt het debiteuradres in. |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | Haalt of stelt het aanvullende ongestructureerde bericht in. |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Haalt of stelt het aanvullende ongestructureerde bericht in. |
|
|  | [getBillInformation()](#getBillInformation--) | Haalt of stelt de aanvullende gestructureerde factuurinformatie in. |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Haalt of stelt de aanvullende gestructureerde factuurinformatie in. |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Maakt een instantie van SwissQR.


### getAmount() {#getAmount--}
```
public final double getAmount()
```


Haalt op of stelt het betalingsbedrag in.
Geldige waarden liggen tussen 0,01 en 999.999.999,99.
Waarde: Het betalingsbedrag.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Haalt op of stelt het betalingsbedrag in.
Geldige waarden liggen tussen 0,01 en 999.999.999,99.
Waarde: Het betalingsbedrag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Haalt op of stelt de betaalvaluta in.
Geldige waarden zijn "CHF" en "EUR".
Waarde: De betaalvaluta.


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Haalt op of stelt de betaalvaluta in.
Geldige waarden zijn "CHF" en "EUR".
Waarde: De betaalvaluta.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Haalt op of stelt het rekeningnummer van de crediteur in.
Rekeningnummers moeten geldige IBAN's zijn van een bank uit Zwitserland of Liechtenstein.
Spaties zijn toegestaan in het rekeningnummer.
Waarde: Het crediteurenrekeningnummer.


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Haalt op of stelt het rekeningnummer van de crediteur in.
Rekeningnummers moeten geldige IBAN's zijn van een bank uit Zwitserland of Liechtenstein.
Spaties zijn toegestaan in het rekeningnummer.
Waarde: Het crediteurenrekeningnummer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Haalt op of stelt het crediteuradres in.
Waarde: Het crediteurenadres.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Haalt op of stelt het crediteuradres in.
Waarde: Het crediteurenadres.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Haalt of stelt de crediteur betalingsreferentie in.
De referentie is verplicht voor SwissQR-IBAN's, d.w.z. IBAN's in het bereik CHxx30000xxxxxx
tot CHxx31999xxxxx.
Indien gespecificeerd, moet de referentie een geldige SwissQR-referentie zijn (overeenkomend
met ISR-referentieformaat) of een geldige crediteurreferentie volgens ISO 11649 ("RFxxxx").
Beiden mogen spaties bevatten voor opmaak.
Waarde: De crediteur betalingsreferentie.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Haalt of stelt de crediteur betalingsreferentie in.
De referentie is verplicht voor SwissQR-IBAN's, d.w.z. IBAN's in het bereik CHxx30000xxxxxx
tot CHxx31999xxxxx.
Indien gespecificeerd, moet de referentie een geldige SwissQR-referentie zijn (overeenkomend
met ISR-referentieformaat) of een geldige crediteurreferentie volgens ISO 11649 ("RFxxxx").
Beiden mogen spaties bevatten voor opmaak.
Waarde: De crediteur betalingsreferentie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Haalt of stelt het debiteuradres in.
De debiteur is optioneel. Indien weggelaten, zowel het instellen van dit veld op null als
het instellen van een adres met alle null- of lege waarden is toegestaan.
Waarde: Het debiteuradres.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Haalt of stelt het debiteuradres in.
De debiteur is optioneel. Indien weggelaten, zowel het instellen van dit veld op null als
het instellen van een adres met alle null- of lege waarden is toegestaan.
Waarde: Het debiteuradres.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Haalt of stelt het aanvullende ongestructureerde bericht in.
Waarde: Het ongestructureerde bericht.


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Haalt of stelt het aanvullende ongestructureerde bericht in.
Waarde: Het ongestructureerde bericht.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Haalt of stelt de aanvullende gestructureerde factuurinformatie in.
Waarde: De gestructureerde factuurinformatie.


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Haalt of stelt de aanvullende gestructureerde factuurinformatie in.
Waarde: De gestructureerde factuurinformatie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

