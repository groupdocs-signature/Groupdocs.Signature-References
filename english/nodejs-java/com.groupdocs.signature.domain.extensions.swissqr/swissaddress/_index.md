---
title: SwissAddress
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the address of the creditor or debtor.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Represents the address of the creditor or debtor. You can either set street, house number, postal code, and town (structured address type) or address line 1 and 2 (combined address elements type).
## Constructors

| Constructor | Description |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets or sets the name, either the first and last name of a natural person or the company name of a legal person. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the name, either the first and last name of a natural person or the company name of a legal person. |
| [getAddressLine1()](#getAddressLine1--) | Gets or sets the address line 1. |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Gets or sets the address line 1. |
| [getAddressLine2()](#getAddressLine2--) | Gets or sets the address line 2. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Gets or sets the address line 2. |
| [getStreet()](#getStreet--) | Gets or sets the street. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Gets or sets the street. |
| [getHouseNo()](#getHouseNo--) | Gets or sets the house number. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Gets or sets the house number. |
| [getPostalCode()](#getPostalCode--) | Gets or sets the postal code. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Gets or sets the postal code. |
| [getTown()](#getTown--) | Gets or sets the town or city. |
| [setTown(String value)](#setTown-java.lang.String-) | Gets or sets the town or city. |
| [getCountryCode()](#getCountryCode--) | Gets or sets the two-letter ISO country code. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Gets or sets the two-letter ISO country code. |
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Gets or sets the name, either the first and last name of a natural person or the company name of a legal person.

Value: The name.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets the name, either the first and last name of a natural person or the company name of a legal person.

Value: The name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Gets or sets the address line 1. Address line 1 contains street name, house number or P.O. box. This field is only used for combined elements addresses and is optional.

Value: The address line 1.

**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Gets or sets the address line 1. Address line 1 contains street name, house number or P.O. box. This field is only used for combined elements addresses and is optional.

Value: The address line 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Gets or sets the address line 2. Address line 2 contains postal code and town. This field is only used for combined elements addresses. For this type, it's mandatory.

Value: The address line 2.

**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Gets or sets the address line 2. Address line 2 contains postal code and town. This field is only used for combined elements addresses. For this type, it's mandatory.

Value: The address line 2.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Gets or sets the street. The street must be specified without a house number. This field is only used for structured addresses and is optional.

Value: The street.

**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Gets or sets the street. The street must be specified without a house number. This field is only used for structured addresses and is optional.

Value: The street.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Gets or sets the house number. This field is only used for structured addresses and is optional.

Value: The house number.

**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Gets or sets the house number. This field is only used for structured addresses and is optional.

Value: The house number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Gets or sets the postal code. This field is only used for structured addresses. For this type, it's mandatory.

Value: The postal code.

**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Gets or sets the postal code. This field is only used for structured addresses. For this type, it's mandatory.

Value: The postal code.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Gets or sets the town or city. This field is only used for structured addresses. For this type, it's mandatory.

Value: The town or city.

**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Gets or sets the town or city. This field is only used for structured addresses. For this type, it's mandatory.

Value: The town or city.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Gets or sets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or empty values.

Value: The ISO country code.

**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Gets or sets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or empty values.

Value: The ISO country code.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

