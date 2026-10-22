---
title: "SearchOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات استخراج التوقيعات من المستند."
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

يمثل خيارات استخراج التوقيعات من المستند.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | يحصل أو يضبط رقم صفحة المستند للبحث. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | يحصل أو يضبط رقم صفحة المستند للبحث. |
| [getPagesSetup()](#getPagesSetup--) | خيارات لتحديد الصفحات للبحث عن التوقيع. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | خيارات لتحديد الصفحات للبحث عن التوقيع. |
| [getAllPages()](#getAllPages--) | علامة للبحث في كل صفحة من المستند. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | علامة للبحث في كل صفحة من المستند. |
| [getSkipExternal()](#getSkipExternal--) | علامة لإرجاع التواقيع التي تم تعليمها كـ IsSignature فقط. |
| [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | علامة لإرجاع التواقيع التي تم تعليمها كـ IsSignature فقط. |
| [getSearchPages(int totalPages)](#getSearchPages-int-) | طريقة افتراضية للحصول على قائمة الصفحات لاستخراج التوقيع. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


يحصل أو يضبط رقم صفحة المستند للبحث. القيمة اختيارية.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


يحصل أو يضبط رقم صفحة المستند للبحث. القيمة اختيارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


خيارات لتحديد الصفحات للبحث عن التوقيع.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


خيارات لتحديد الصفحات للبحث عن التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


علامة للبحث في كل صفحة من المستند. بشكل افتراضي يتم تعيين هذه القيمة إلى true.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


علامة للبحث في كل صفحة من المستند. بشكل افتراضي يتم تعيين هذه القيمة إلى true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


علامة لإرجاع التواقيع التي تم تعليمها كـ IsSignature فقط. بشكل افتراضي القيمة هي false مما يعني إرجاع جميع التواقيع التي تطابق المعايير المحددة.

**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


علامة لإرجاع التواقيع التي تم تعليمها كـ IsSignature فقط. بشكل افتراضي القيمة هي false مما يعني إرجاع جميع التواقيع التي تطابق المعايير المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


طريقة افتراضية للحصول على قائمة الصفحات لاستخراج التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| totalPages | int | العدد الكلي للصفحات |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - قائمة أرقام الصفحات
### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.

**Returns:**
java.lang.String -
