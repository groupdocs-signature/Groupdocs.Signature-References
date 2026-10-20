---
title: "Mailmark2D"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Klass för kodning och avkodning av text som är inbäddad i Royal Mail 2D Mailmark"
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Klass för kodning och avkodning av text som är inbäddad i Royal Mail 2D Mailmark

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | Skapar kombinerad data för Royal Mail Mailmark med standardvärden för primära och sekundära data. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | Identifierar UPU-land-ID. Maxlängd: 4 tecken. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifierar UPU-land-ID. Maxlängd: 4 tecken. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | Identifierar Royal Mail Mailmark streckkodspayload för varje produkttyp. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifierar Royal Mail Mailmark streckkodspayload för varje produkttyp. |
|
|  | [getVersionID()](#getVersionID--) | Identifierar streckkodsversionen som relevant för varje Information Type ID. |
|
|  | [getClass_()](#getClass---) | Identifierar objektets klass. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | Identifierar objektets klass. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | Identifierar den unika gruppen av kunder som är involverade i utskicket. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifierar den unika gruppen av kunder som är involverade i utskicket. |
|
|  | [getItemID()](#getItemID--) | Identifierar det unika objektet inom Supply Chain ID. |
|
|  | [setItemID(int value)](#setItemID-int-) | Identifierar det unika objektet inom Supply Chain ID. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Innehåller postnumret för leveransadressen med DPS |
Om inrikes innehåller postnumret/DP följande antal tecken.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Innehåller postnumret för leveransadressen med DPS |
Om inrikes innehåller postnumret/DP följande antal tecken.
|
|  | [getRTSFlag()](#getRTSFlag--) | Flagga som indikerar vilken nivå av Return to Sender-tjänst som begärs. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Flagga som indikerar vilken nivå av Return to Sender-tjänst som begärs. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Innehåller Return to Sender-postkoden men ingen DPS. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Innehåller Return to Sender-postkoden men ingen DPS. |
|
|  | [getCustomerContent()](#getCustomerContent--) | Valfritt utrymme för kundens bruk. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Valfritt utrymme för kundens bruk. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Koda läge för DataMatrix-streckkod. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Koda läge för DataMatrix-streckkod. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark-typ definierar storleken på Data Matrix-streckkoden. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | 2D Mailmark-typ definierar storleken på Data Matrix-streckkoden. |
|
|  | [deepClone()](#deepClone--) | Hämtar en kopia av detta objekt. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Skapar kombinerad data för Royal Mail Mailmark med standardvärden för primära och sekundära data.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Identifierar UPU-land-ID. Maxlängd: 4 tecken.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Identifierar UPU-land-ID. Maxlängd: 4 tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Identifierar Royal Mail Mailmark streckkodspayload för varje produkttyp.

<br />

*** ** * ** ***

Giltiga värden: \"0\" - Inrikes sorterat och osorterat \"A\" - Online-postering \"B\" - Frankering \"C\" - Konsolidering

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Identifierar Royal Mail Mailmark streckkodspayload för varje produkttyp.

<br />

*** ** * ** ***

Giltiga värden: \"0\" - Inrikes sorterat och osorterat \"A\" - Online-postering \"B\" - Frankering \"C\" - Konsolidering

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Identifierar streckkodsversionen som relevant för varje Information Type ID.

<br />

*** ** * ** ***

Giltiga värden: "1" - för närvarande används endast detta värde (standard) "0" och "2" till "9" och "A" till "Z" reserveras för potentiell framtida användning.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Identifierar objektets klass.

<br />

*** ** * ** ***

Giltiga värden: "1" - 1C (Detaljhandel) "2" - 2C(Detaljhandel) "3" - Ekonomi(Detaljhandel) "5" - Uppskjuten(Detaljhandel) "8" - Premium(Nätverksåtkomst) "9" - Standard(Nätverksåtkomst)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Identifierar objektets klass.

<br />

*** ** * ** ***

Giltiga värden: "1" - 1C (Detaljhandel) "2" - 2C(Detaljhandel) "3" - Ekonomi(Detaljhandel) "5" - Uppskjuten(Detaljhandel) "8" - Premium(Nätverksåtkomst) "9" - Standard(Nätverksåtkomst)

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Identifierar den unika gruppen av kunder som är involverade i utskicket.
Maxvärde: 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Identifierar den unika gruppen av kunder som är involverade i utskicket.
Maxvärde: 9999999.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Identifierar det unika objektet inom Supply Chain ID.
Varje Mailmark-streckkod måste bära ett ID så att den kan identifieras unikt i minst 90 dagar.
Maxvärde: 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Identifierar det unika objektet inom Supply Chain ID.
Varje Mailmark-streckkod måste bära ett ID så att den kan identifieras unikt i minst 90 dagar.
Maxvärde: 99999999.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Innehåller postnumret för leveransadressen med DPS
Om inrikes innehåller postnumret/DP följande antal tecken.
Område (1 eller 2 tecken)
Distrikt(1 eller 2 tecken)
Sektor(1 tecken)
Enhet(2 tecken)
DPS (2 tecken).
Postnumret och DPS måste följa ett giltigt PAF®-format. Maxlängd är 9.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Innehåller postnumret för leveransadressen med DPS
Om inrikes innehåller postnumret/DP följande antal tecken.
Område (1 eller 2 tecken)
Distrikt(1 eller 2 tecken)
Sektor(1 tecken)
Enhet(2 tecken)
DPS (2 tecken).
Postnumret och DPS måste följa ett giltigt PAF®-format. Maxlängd är 9.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Flagga som indikerar vilken nivå av Return to Sender-tjänst som begärs. Maxlängd är 1


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Flagga som indikerar vilken nivå av Return to Sender-tjänst som begärs. Maxlängd är 1


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Innehåller Return to Sender-postkoden men ingen DPS.
PC(utan DPS) måste följa ett PAF®-format.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Innehåller Return to Sender-postkoden men ingen DPS.
PC(utan DPS) måste följa ett PAF®-format.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Valfritt utrymme för kundens bruk.

<br />

*** ** * ** ***

Maxlängd per typ [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Typ 7: 6 tecken Typ 9: 45 tecken Typ 29: 25 tecken

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Valfritt utrymme för kundens bruk.

<br />

*** ** * ** ***

Maxlängd per typ [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Typ 7: 6 tecken Typ 9: 45 tecken Typ 29: 25 tecken

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Kodningsläge för DataMatrix-streckkod. Standardvärde: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Kodningsläge för DataMatrix-streckkod. Standardvärde: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


2D Mailmark-typ definierar storleken på Data Matrix-streckkoden.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


2D Mailmark-typ definierar storleken på Data Matrix-streckkoden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Hämtar en kopia av detta objekt.


**Returns:**
java.lang.Object
