---
title: EPC
second_title: GroupDocs.Signature for Java API Reference
description: Represents European Payments Council Quick Response Code.
type: docs
weight: 14
url: /java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Represents European Payments Council Quick Response Code.
## Constructors

| Constructor | Description |
| --- | --- |
| [EPC()](#EPC--) | Instantiates new EPC object. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets or sets Beneficiary's Name. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets Beneficiary's Name. |
| [getBIC()](#getBIC--) | Gets or sets Beneficiary's BIC with up to 11 characters length. |
| [setBIC(String value)](#setBIC-java.lang.String-) | Gets or sets Beneficiary's BIC with up to 11 characters length. |
| [getIBAN()](#getIBAN--) | Gets or sets Beneficiary's Account (IBAN). |
| [setIBAN(String value)](#setIBAN-java.lang.String-) | Gets or sets Beneficiary's Account (IBAN). |
| [getAmount()](#getAmount--) | Gets or sets amount. |
| [setAmount(double value)](#setAmount-double-) | Gets or sets amount. |
| [getCode()](#getCode--) | Gets or sets Business Code up to 4 characters. |
| [setCode(String value)](#setCode-java.lang.String-) | Gets or sets Business Code up to 4 characters. |
| [getReference()](#getReference--) | Gets or sets Payment Reference (maximum 35 characters). |
| [setReference(String value)](#setReference-java.lang.String-) | Gets or sets Payment Reference (maximum 35 characters). |
| [getRemittance()](#getRemittance--) | Gets or sets Remittance Information (maximum 140 characters). |
| [setRemittance(String value)](#setRemittance-java.lang.String-) | Gets or sets Remittance Information (maximum 140 characters). |
| [getInformation()](#getInformation--) | Gets or sets hint information. |
| [setInformation(String value)](#setInformation-java.lang.String-) | Gets or sets hint information. |
| [getVersion()](#getVersion--) | EPC / SEPA QR-Code version implementation. |
| [setVersion(String value)](#setVersion-java.lang.String-) | EPC / SEPA QR-Code version implementation. |
| [getCharset()](#getCharset--) | EPC / SEPA QR-Code char set implementation. |
| [setCharset(String value)](#setCharset-java.lang.String-) | EPC / SEPA QR-Code char set implementation. |
| [getIdentification()](#getIdentification--) | EPC / SEPA QR-Code identification. |
| [setIdentification(String value)](#setIdentification-java.lang.String-) | EPC / SEPA QR-Code identification. |
| [equals(Object source)](#equals-java.lang.Object-) | Overwrites Equals method to compare EPC properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
### EPC() {#EPC--}
```
public EPC()
```


Instantiates new EPC object.

### getName() {#getName--}
```
public final String getName()
```


Gets or sets Beneficiary's Name. Maximum length is 70 characters.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets Beneficiary's Name. Maximum length is 70 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Gets or sets Beneficiary's BIC with up to 11 characters length.

**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Gets or sets Beneficiary's BIC with up to 11 characters length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Gets or sets Beneficiary's Account (IBAN). The IBAN consists of up to 34 alphanumeric characters.

**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Gets or sets Beneficiary's Account (IBAN). The IBAN consists of up to 34 alphanumeric characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Gets or sets amount.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Gets or sets amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Gets or sets Business Code up to 4 characters.

**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Gets or sets Business Code up to 4 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Gets or sets Payment Reference (maximum 35 characters). This field and the Remittance Information field are mutually exclusive.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Gets or sets Payment Reference (maximum 35 characters). This field and the Remittance Information field are mutually exclusive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Gets or sets Remittance Information (maximum 140 characters). This field and the Payment Reference field are mutually exclusive.

**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Gets or sets Remittance Information (maximum 140 characters). This field and the Payment Reference field are mutually exclusive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Gets or sets hint information. Maximum 70 characters.

**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Gets or sets hint information. Maximum 70 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


EPC / SEPA QR-Code version implementation. By default this value set to 002.

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


EPC / SEPA QR-Code version implementation. By default this value set to 002.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


EPC / SEPA QR-Code char set implementation. By default this value set to 1

**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


EPC / SEPA QR-Code char set implementation. By default this value set to 1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


EPC / SEPA QR-Code identification. By default this value set to SCT

**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


EPC / SEPA QR-Code identification. By default this value set to SCT

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Overwrites Equals method to compare EPC properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.Object | EPC object to compare with. |

**Returns:**
boolean - Returns true if passed address object has same type and all its properties are equal to this instance properties.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Overrides GetHashCode method

**Returns:**
int - Email hash code
