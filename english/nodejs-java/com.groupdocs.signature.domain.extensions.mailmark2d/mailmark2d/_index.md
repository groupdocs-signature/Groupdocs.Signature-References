---
title: Mailmark2D
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark
## Constructors

| Constructor | Description |
| --- | --- |
| [Mailmark2D()](#Mailmark2D--) | Creates Royal Mail Mailmark combined data with default primary and secondary data values. |
## Methods

| Method | Description |
| --- | --- |
| [getUPUCountryID()](#getUPUCountryID--) | Identifies the UPU Country ID.Max length: 4 characters. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifies the UPU Country ID.Max length: 4 characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getVersionID()](#getVersionID--) | Identifies the barcode version as relevant to each Information Type ID. |
| [getClass_()](#getClass---) | Identifies the class of the item. |
| [setClass(String value)](#setClass-java.lang.String-) | Identifies the class of the item. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifies the unique group of customers involved in the mailing. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifies the unique group of customers involved in the mailing. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getRTSFlag()](#getRTSFlag--) | Flag which indicates what level of Return to Sender service is being requested. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Flag which indicates what level of Return to Sender service is being requested. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contains the Return to Sender Post Code but no DPS. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contains the Return to Sender Post Code but no DPS. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of DataMatrix barcode. |
| [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Encode mode of DataMatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDataMatrixType(int value)](#setDataMatrixType-int-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [deepClone()](#deepClone--) | Gets a copy of this object. |
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Creates Royal Mail Mailmark combined data with default primary and secondary data values.

### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Identifies the UPU Country ID.Max length: 4 characters.

**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Identifies the UPU Country ID.Max length: 4 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Identifies the Royal Mail Mailmark barcode payload for each product type.

--------------------

Valid Values: "0" - Domestic Sorted and Unsorted "A" - On-line Postage "B" - Franking "C" - Consolidation

**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Identifies the Royal Mail Mailmark barcode payload for each product type.

--------------------

Valid Values: "0" - Domestic Sorted and Unsorted "A" - On-line Postage "B" - Franking "C" - Consolidation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Identifies the barcode version as relevant to each Information Type ID.

--------------------

Valid Values: "1" - currently used only this value (default) "0" and "2" to "9" and "A" to "Z" spare reserved for potential future use.

**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Identifies the class of the item.

--------------------

Valid Values: "1" - 1C (Retail) "2" - 2C(Retail) "3" - Economy(Retail) "5" - Deferred(Retail) "8" - Premium(Network Access) "9" - Standard(Network Access)

**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Identifies the class of the item.

--------------------

Valid Values: "1" - 1C (Retail) "2" - 2C(Retail) "3" - Economy(Retail) "5" - Deferred(Retail) "8" - Premium(Network Access) "9" - Standard(Network Access)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Identifies the unique group of customers involved in the mailing. Max value: 9999999.

**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Identifies the unique group of customers involved in the mailing. Max value: 9999999.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999.

**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. Max length is 9.

**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. Max length is 9.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Flag which indicates what level of Return to Sender service is being requested. Max length is 1

**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Flag which indicates what level of Return to Sender service is being requested. Max length is 1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format.

**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Optional space for use by customer.

--------------------

Max length by Type [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters

**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Optional space for use by customer.

--------------------

Max length by Type [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Encode mode of DataMatrix barcode. Default value: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Encode mode of DataMatrix barcode. Default value: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Gets a copy of this object.

**Returns:**
java.lang.Object
