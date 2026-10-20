---
title: "Mailmark2D"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark"
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | Maakt gecombineerde Royal Mail Mailmark-gegevens met standaard primaire en secundaire gegevenswaarden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | Identificeert de UPU-land-ID.Maximale lengte: 4 tekens. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identificeert de UPU-land-ID.Maximale lengte: 4 tekens. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | Identificeert de Royal Mail Mailmark barcodepayload voor elk producttype. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identificeert de Royal Mail Mailmark barcodepayload voor elk producttype. |
|
|  | [getVersionID()](#getVersionID--) | Identificeert de barcodeversie die relevant is voor elke informatie-type-ID. |
|
|  | [getClass_()](#getClass---) | Identificeert de klasse van het item. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | Identificeert de klasse van het item. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | Identificeert de unieke groep klanten die bij de verzending betrokken zijn. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identificeert de unieke groep klanten die bij de verzending betrokken zijn. |
|
|  | [getItemID()](#getItemID--) | Identificeert het unieke item binnen de supply chain-ID. |
|
|  | [setItemID(int value)](#setItemID-int-) | Identificeert het unieke item binnen de supply chain-ID. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Bevat de postcode van het afleveradres met DPS |
Als binnenland bevat de postcode/DP het volgende aantal tekens.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Bevat de postcode van het afleveradres met DPS |
Als binnenland bevat de postcode/DP het volgende aantal tekens.
|
|  | [getRTSFlag()](#getRTSFlag--) | Vlag die aangeeft welk niveau van Retour naar Afzender-service wordt aangevraagd. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Vlag die aangeeft welk niveau van Retour naar Afzender-service wordt aangevraagd. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Bevat de Retour naar Afzender-postcode maar geen DPS. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Bevat de Retour naar Afzender-postcode maar geen DPS. |
|
|  | [getCustomerContent()](#getCustomerContent--) | Optionele ruimte voor gebruik door de klant. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optionele ruimte voor gebruik door de klant. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encodeermodus van DataMatrix-barcode. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Encodeermodus van DataMatrix-barcode. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
|
|  | [deepClone()](#deepClone--) | Krijgt een kopie van dit object. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Maakt gecombineerde Royal Mail Mailmark-gegevens met standaard primaire en secundaire gegevenswaarden.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Identificeert de UPU-land-ID.Maximale lengte: 4 tekens.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Identificeert de UPU-land-ID.Maximale lengte: 4 tekens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Identificeert de Royal Mail Mailmark barcodepayload voor elk producttype.

<br />

*** ** * ** ***

Geldige waarden: "0" - Binnenlands gesorteerd en onsorteerd "A" - Online postzegel "B" - Frankering "C" - Consolidatie

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Identificeert de Royal Mail Mailmark barcodepayload voor elk producttype.

<br />

*** ** * ** ***

Geldige waarden: "0" - Binnenlands gesorteerd en onsorteerd "A" - Online postzegel "B" - Frankering "C" - Consolidatie

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Identificeert de barcodeversie die relevant is voor elke informatie-type-ID.

<br />

*** ** * ** ***

Geldige waarden: "1" - momenteel alleen deze waarde gebruikt (standaard) "0" en "2" tot "9" en "A" tot "Z" reserve voor mogelijk toekomstig gebruik.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Identificeert de klasse van het item.

<br />

*** ** * ** ***

Geldige waarden: "1" - 1C (Retail) "2" - 2C (Retail) "3" - Economy (Retail) "5" - Deferred (Retail) "8" - Premium (Network Access) "9" - Standard (Network Access)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Identificeert de klasse van het item.

<br />

*** ** * ** ***

Geldige waarden: "1" - 1C (Retail) "2" - 2C (Retail) "3" - Economy (Retail) "5" - Deferred (Retail) "8" - Premium (Network Access) "9" - Standard (Network Access)

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Identificeert de unieke groep klanten die bij de verzending betrokken zijn.
Maximumwaarde: 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Identificeert de unieke groep klanten die bij de verzending betrokken zijn.
Maximumwaarde: 9999999.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Identificeert het unieke item binnen de supply chain-ID.
Elke Mailmark-barcode moet een ID dragen zodat deze gedurende minstens 90 dagen uniek kan worden geïdentificeerd.
Maximumwaarde: 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Identificeert het unieke item binnen de supply chain-ID.
Elke Mailmark-barcode moet een ID dragen zodat deze gedurende minstens 90 dagen uniek kan worden geïdentificeerd.
Maximumwaarde: 99999999.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Bevat de postcode van het afleveradres met DPS
Als binnenland bevat de postcode/DP het volgende aantal tekens.
Gebied (1 of 2 tekens)
District(1 of 2 tekens)
Sector(1 teken)
Unit(2 tekens)
DPS (2 tekens).
De postcode en DPS moeten voldoen aan een geldig PAF®-formaat. Maximale lengte is 9.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Bevat de postcode van het afleveradres met DPS
Als binnenland bevat de postcode/DP het volgende aantal tekens.
Gebied (1 of 2 tekens)
District(1 of 2 tekens)
Sector(1 teken)
Unit(2 tekens)
DPS (2 tekens).
De postcode en DPS moeten voldoen aan een geldig PAF®-formaat. Maximale lengte is 9.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd. Maximale lengte is 1


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd. Maximale lengte is 1


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Bevat de Retour naar Afzender-postcode maar geen DPS.
De PC(without DPS) moet voldoen aan een PAF®-formaat.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Bevat de Retour naar Afzender-postcode maar geen DPS.
De PC(without DPS) moet voldoen aan een PAF®-formaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Optionele ruimte voor gebruik door de klant.

<br />

*** ** * ** ***

Maximale lengte per type [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Type 7: 6 tekens Type 9: 45 tekens Type 29: 25 tekens

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Optionele ruimte voor gebruik door de klant.

<br />

*** ** * ** ***

Maximale lengte per type [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Type 7: 6 tekens Type 9: 45 tekens Type 29: 25 tekens

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Coderingsmodus van DataMatrix-barcode. Standaardwaarde: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Coderingsmodus van DataMatrix-barcode. Standaardwaarde: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


2D Mailmark-type definieert de grootte van de Data Matrix-barcode.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


2D Mailmark-type definieert de grootte van de Data Matrix-barcode.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Krijgt een kopie van dit object.


**Returns:**
java.lang.Object
