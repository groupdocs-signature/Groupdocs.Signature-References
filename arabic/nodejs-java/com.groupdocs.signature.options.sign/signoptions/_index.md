---
title: "SignOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات التوقيع."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

يمثل خيارات التوقيع.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | يحصل أو يعيّن رقم صفحة المستند للتوقيع. |
| [setPageNumber(int value)](#setPageNumber-int-) | يحصل أو يعيّن رقم صفحة المستند للتوقيع. |
| [getAllPages()](#getAllPages--) | ضع التوقيع على جميع صفحات المستند. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | ضع التوقيع على جميع صفحات المستند. |
| [getAppearance()](#getAppearance--) | مظهر توقيع إضافي. |
| [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | مظهر توقيع إضافي. |
| [getExtensions()](#getExtensions--) | امتدادات التوقيع. |
| [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | امتدادات التوقيع. |
| [getPagesSetup()](#getPagesSetup--) | خيارات لتحديد الصفحات التي سيتم توقيعها. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | خيارات لتحديد الصفحات التي سيتم توقيعها. |
| [getSignatureType()](#getSignatureType--) | احصل على نوع التوقيع [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
| [getDocumentType()](#getDocumentType--) | احصل أو عيّن نوع المستند لخيارات التوقيع [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [setDocumentType(int value)](#setDocumentType-int-) | احصل أو عيّن نوع المستند لخيارات التوقيع [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [getZOrder()](#getZOrder--) | يحصل أو يعيّن موضع Z-order لتوقيع النص. |
| [setZOrder(int value)](#setZOrder-int-) | يحصل أو يعيّن موضع Z-order لتوقيع النص. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


يحصل أو يعيّن رقم صفحة المستند للتوقيع. الحد الأدنى والقيمة الافتراضية هي 1.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


يحصل أو يعيّن رقم صفحة المستند للتوقيع. الحد الأدنى والقيمة الافتراضية هي 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


ضع التوقيع على جميع صفحات المستند.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


ضع التوقيع على جميع صفحات المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


مظهر توقيع إضافي.

**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


مظهر توقيع إضافي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


امتدادات التوقيع.

**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


امتدادات التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


خيارات لتحديد الصفحات التي سيتم توقيعها.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


خيارات لتحديد الصفحات التي سيتم توقيعها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


احصل على نوع التوقيع [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)

**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


احصل أو عيّن نوع المستند لخيارات التوقيع [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


احصل أو عيّن نوع المستند لخيارات التوقيع [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


يحصل أو يضبط موضع Z-order لتوقيع النص. يحدد ترتيب العرض للتواقيع المتداخلة.

**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


يحصل أو يضبط موضع Z-order لتوقيع النص. يحدد ترتيب العرض للتواقيع المتداخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.

**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
