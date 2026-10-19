---
title: "VerifyOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحافظ على خيارات التحقق من المستند."
type: docs
weight: 15
url: /ar/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

يحافظ على خيارات التحقق من المستند.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid()](#isValid--) | علامة الخاصية الصالحة. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | علامة الخاصية الصالحة. |
|
|  | [getPageNumber()](#getPageNumber--) | رقم صفحة المستند للتحقق. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | رقم صفحة المستند للتحقق. |
|
|  | [getPagesSetup()](#getPagesSetup--) | خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها. |
|
|  | [getAllPages()](#getAllPages--) | علامة للتحقق من كل صفحة في المستند. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | علامة للتحقق من كل صفحة في المستند. |
|
|  | [getExtensions()](#getExtensions--) | امتدادات إضافية للتحقق من خيارات التوقيع البديلة. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | امتدادات إضافية للتحقق من خيارات التوقيع البديلة. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


علامة الخاصية الصالحة.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


علامة الخاصية الصالحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


رقم صفحة المستند للتحقق. إذا لم يتم تعيين الخاصية - جميع صفحات
سيتم التحقق من المستند للظهور الأول.
القيمة الدنيا هي 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


رقم صفحة المستند للتحقق. إذا لم يتم تعيين الخاصية - جميع صفحات
سيتم التحقق من المستند للظهور الأول.
القيمة الدنيا هي 1.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


علامة للتحقق من كل صفحة في المستند. القيمة الافتراضية هي true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


علامة للتحقق من كل صفحة في المستند. القيمة الافتراضية هي true.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


امتدادات إضافية للتحقق من خيارات التوقيع البديلة.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


امتدادات إضافية للتحقق من خيارات التوقيع البديلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
