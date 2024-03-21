---
title: SwissQR
second_title: GroupDocs.Signature for Java API Reference
description: Class for encoding and decoding the text embedded in the SwissQR code.
type: docs
weight: 11
url: /java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Class for encoding and decoding the text embedded in the SwissQR code.
## Constructors

| Constructor | Description |
| --- | --- |
| [SwissQR()](#SwissQR--) | Creates an instance of SwissQR. |
## Methods

| Method | Description |
| --- | --- |
| [getAmount()](#getAmount--) | Gets or sets the payment amount. |
| [setAmount(double value)](#setAmount-double-) | Gets or sets the payment amount. |
| [getCurrency()](#getCurrency--) | Gets or sets the payment currency. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Gets or sets the payment currency. |
| [getAccount()](#getAccount--) | Gets or sets the creditor's account number. |
| [setAccount(String value)](#setAccount-java.lang.String-) | Gets or sets the creditor's account number. |
| [getCreditor()](#getCreditor--) | Gets or sets the creditor address. |
| [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Gets or sets the creditor address. |
| [getReference()](#getReference--) | Gets or sets the creditor payment reference. |
| [setReference(String value)](#setReference-java.lang.String-) | Gets or sets the creditor payment reference. |
| [getDebtor()](#getDebtor--) | Gets or sets the debtor address. |
| [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Gets or sets the debtor address. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Gets or sets the additional unstructured message. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Gets or sets the additional unstructured message. |
| [getBillInformation()](#getBillInformation--) | Gets or sets the additional structured bill information. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Gets or sets the additional structured bill information. |
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Creates an instance of SwissQR.

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Gets or sets the payment amount. Valid values are between 0.01 and 999,999,999.99.

Value: The payment amount.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Gets or sets the payment amount. Valid values are between 0.01 and 999,999,999.99.

Value: The payment amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Gets or sets the payment currency. Valid values are "CHF" and "EUR".

Value: The payment currency.

**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Gets or sets the payment currency. Valid values are "CHF" and "EUR".

Value: The payment currency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Gets or sets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number.

Value: The creditor account number.

**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Gets or sets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number.

Value: The creditor account number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Gets or sets the creditor address.

Value: The creditor address.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Gets or sets the creditor address.

Value: The creditor address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Gets or sets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e. IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

Value: The creditor payment reference.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Gets or sets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e. IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

Value: The creditor payment reference.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Gets or sets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address with all null or empty values is ok.

Value: The debtor address.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Gets or sets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address with all null or empty values is ok.

Value: The debtor address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Gets or sets the additional unstructured message.

Value: The unstructured message.

**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Gets or sets the additional unstructured message.

Value: The unstructured message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Gets or sets the additional structured bill information.

Value: The structured bill information.

**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Gets or sets the additional structured bill information.

Value: The structured bill information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

