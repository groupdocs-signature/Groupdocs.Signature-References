---
title: SignOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents the signature options.
type: docs
weight: 16
url: /java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Represents the signature options.
## Methods

| Method | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Gets or sets document page number for signing. |
| [setPageNumber(int value)](#setPageNumber-int-) | Gets or sets document page number for signing. |
| [getAllPages()](#getAllPages--) | Put signature on all document pages. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Put signature on all document pages. |
| [getAppearance()](#getAppearance--) | Additional signature appearance. |
| [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Additional signature appearance. |
| [getExtensions()](#getExtensions--) | Signature Extensions. |
| [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.SignatureExtension--) | Signature Extensions. |
| [getPagesSetup()](#getPagesSetup--) | Options to specify pages to be signed. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Options to specify pages to be signed. |
| [getSignatureType()](#getSignatureType--) | Get the Signature Type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
| [getDocumentType()](#getDocumentType--) | Get or set the Document Type of the Signature Options [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [setDocumentType(int value)](#setDocumentType-int-) | Get or set the Document Type of the Signature Options [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [getZOrder()](#getZOrder--) | Gets or sets the Z-order position of text signature. |
| [setZOrder(int value)](#setZOrder-int-) | Gets or sets the Z-order position of text signature. |
| [toString()](#toString--) | Override string conversion. |
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Gets or sets document page number for signing. Minimal and default value is 1.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Gets or sets document page number for signing. Minimal and default value is 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Put signature on all document pages.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Put signature on all document pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Additional signature appearance.

**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Additional signature appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Signature Extensions.

**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Signature Extensions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.signature.domain.extensions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Options to specify pages to be signed.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Options to specify pages to be signed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Get the Signature Type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)

**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Get or set the Document Type of the Signature Options [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Get or set the Document Type of the Signature Options [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Gets or sets the Z-order position of text signature. Determines the display order of overlapping signatures.

**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Gets or sets the Z-order position of text signature. Determines the display order of overlapping signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
