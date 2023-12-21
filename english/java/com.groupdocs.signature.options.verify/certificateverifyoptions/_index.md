---
title: CertificateVerifyOptions
second_title: GroupDocs.Signature for Java API Reference
description: Keeps options to verify certificate documents.
type: docs
weight: 11
url: /java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Keeps options to verify certificate documents.

--------------------

 **Learn more** 

 *  
## Constructors

| Constructor | Description |
| --- | --- |
| [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Initializes a new instance of the TextVerifyOptions with default values. |
| [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Initializes a new instance of the CertificateVerifyOptions with subject to verify. |
## Methods

| Method | Description |
| --- | --- |
| [getIssuer()](#getIssuer--) | Specify Certificate Issuer if it should be verified. |
| [setIssuer(String value)](#setIssuer-java.lang.String-) | Specify Certificate Issuer if it should be verified. |
| [getSerialNumber()](#getSerialNumber--) | Specify Certificate Serial Number if it should be verified. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Specify Certificate Serial Number if it should be verified. |
| [getSubject()](#getSubject--) | Specify Certificate subject if it should be verified. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Specify Certificate subject if it should be verified. |
| [getThumbprint()](#getThumbprint--) | Specify Certificate Thumbprint if it should be verified. |
| [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Specify Certificate Thumbprint if it should be verified. |
| [getMatchType()](#getMatchType--) | Gets or sets Text Match Type verification. |
| [setMatchType(int value)](#setMatchType-int-) | Gets or sets Text Match Type verification. |
| [getExpired()](#getExpired--) | Indicates if certificate is expired date due validation result. |
| [setExpired(boolean value)](#setExpired-boolean-) | Indicates if certificate is expired date due validation result. |
| [getPerformChainValidation()](#getPerformChainValidation--) | Get or set if verification process should provide X.509 chain validation using basic validation policy. |
| [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Get or set if verification process should provide X.509 chain validation using basic validation policy. |
| [toString()](#toString--) | Overrides conversion to string. |
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Initializes a new instance of the TextVerifyOptions with default values.

### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Initializes a new instance of the CertificateVerifyOptions with subject to verify.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subject | java.lang.String | Subject to be verified |

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Specify Certificate Issuer if it should be verified.

**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Specify Certificate Issuer if it should be verified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Specify Certificate Serial Number if it should be verified.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Specify Certificate Serial Number if it should be verified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Specify Certificate subject if it should be verified.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Specify Certificate subject if it should be verified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Specify Certificate Thumbprint if it should be verified.

**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Specify Certificate Thumbprint if it should be verified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Gets or sets Text Match Type verification.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Gets or sets Text Match Type verification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Indicates if certificate is expired date due validation result. Property is read-only.

**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Indicates if certificate is expired date due validation result. Property is read-only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Get or set if verification process should provide X.509 chain validation using basic validation policy. By default this value is true.

**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Get or set if verification process should provide X.509 chain validation using basic validation policy. By default this value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Overrides conversion to string.

**Returns:**
java.lang.String - 
