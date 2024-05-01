---
title: DigitalVBA
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents digital signature for Spreadsheets VBA projects.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Represents digital signature for Spreadsheets VBA projects. It provides ability to sign VBA project at specific Spreadsheets document formats like Xlsm or Xltm. If several DigitalVBA extensions are added to DigitalSignOptions.Extensions only first is involved in document signing.
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Initializes a new instance of the DigitalVBA class with certificate file. |
| [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Initializes a new instance of the DigitalVBA class with certificate stream. |
## Methods

| Method | Description |
| --- | --- |
| [getComments()](#getComments--) | Gets or sets the signature comments. |
| [setComments(String value)](#setComments-java.lang.String-) | Gets or sets the signature comments. |
| [getPassword()](#getPassword--) | Gets or sets the password of digital certificate. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets the password of digital certificate. |
| [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Gets or sets setting of only VBA project signing. |
| [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Gets or sets setting of only VBA project signing. |
| [getCertificateFilePath()](#getCertificateFilePath--) | Gets digital certificate file path. |
| [getCertificateStream()](#getCertificateStream--) | Gets digital certificate stream. |
| [release()](#release--) | Override method to clean up resources after signing. |
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Initializes a new instance of the DigitalVBA class with certificate file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Digital certificate file path |
| password | java.lang.String | Digital certificate password |

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Initializes a new instance of the DigitalVBA class with certificate stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Digital Certificate stream |
| password | java.lang.String | Digital certificate password |

### getComments() {#getComments--}
```
public final String getComments()
```


Gets or sets the signature comments.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Gets or sets the signature comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets or sets the password of digital certificate.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Gets or sets the password of digital certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Gets or sets setting of only VBA project signing. If set to true, the SpreadSheet document will not be signed, but the VBA project will be signed.

**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Gets or sets setting of only VBA project signing. If set to true, the SpreadSheet document will not be signed, but the VBA project will be signed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Gets digital certificate file path. This property is used only if CertificateStream is not specified.

**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Gets digital certificate stream. If this property is specified it is always used instead CertificateFilePath.

**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Override method to clean up resources after signing.

