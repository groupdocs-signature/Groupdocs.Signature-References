---
title: HIBCLICSecondaryAdditionalData
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Class for storing HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code secondary and additional data.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Class for storing HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) secondary and additional data.
## Constructors

| Constructor | Description |
| --- | --- |
| [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Default ctor() |
## Methods

| Method | Description |
| --- | --- |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifies expiry date format. |
| [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Identifies expiry date format. |
| [getExpiryDate()](#getExpiryDate--) | Identifies expiry date. |
| [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Identifies expiry date. |
| [getLotNumber()](#getLotNumber--) | Identifies lot or batch number. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifies lot or batch number. |
| [getSerialNumber()](#getSerialNumber--) | Identifies serial number. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifies serial number. |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identifies date of manufacture. |
| [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Identifies date of manufacture. |
| [getQuantity()](#getQuantity--) | Identifies quantity, must be integer value from 0 to 500. |
| [setQuantity(int value)](#setQuantity-int-) | Identifies quantity, must be integer value from 0 to 500. |
| [getLinkCharacter()](#getLinkCharacter--) | Identifies link character in output string. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | Identifies link character in output string. |
| [deepClone()](#deepClone--) | Gets a copy of this object. |
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Default ctor()

### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Identifies expiry date format.

**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Identifies expiry date format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Identifies expiry date. Will be used if ExpiryDateFormat is not set to None.

**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Identifies expiry date. Will be used if ExpiryDateFormat is not set to None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 symbols length.

**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 symbols length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Identifies serial number. Serial number must be alphanumeric string up to 18 symbols length.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Identifies serial number. Serial number must be alphanumeric string up to 18 symbols length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue

**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1

**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Identifies link character in output string.

**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Identifies link character in output string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Gets a copy of this object.

**Returns:**
java.lang.Object
