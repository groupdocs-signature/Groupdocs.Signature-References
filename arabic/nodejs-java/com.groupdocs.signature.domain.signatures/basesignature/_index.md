---
title: "BaseSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يصف الفئة الأساسية للتوقيعات."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

يصف الفئة الأساسية للتوقيعات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSignatureType()](#getSignatureType--) | يحدد نوع التوقيع. |
| [getPageNumber()](#getPageNumber--) | يحدد الصفحة التي تم العثور على التوقيع فيها. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | يحدد الصفحة التي تم العثور على التوقيع فيها. |
| [getSignatureId()](#getSignatureId--) | معرف توقيع فريد لتعديل التوقيع في المستند عبر طريقتي Update أو Delete. |
| [isSignature()](#isSignature--) | احصل أو عيّن العلامة لتحديد ما إذا كان هذا المكوّن توقيعًا أم محتوى المستند. |
| [setSignature(boolean value)](#setSignature-boolean-) | احصل أو عيّن العلامة لتحديد ما إذا كان هذا المكوّن توقيعًا أم محتوى المستند. |
| [getDeleted()](#getDeleted--) | احصل أو عيّن العلامة لتحديد ما إذا تم حذف هذا التوقيع من المستند. |
| [getCreatedOn()](#getCreatedOn--) | احصل أو عيّن تاريخ إنشاء التوقيع. |
| [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | احصل أو عيّن تاريخ إنشاء التوقيع. |
| [getModifiedOn()](#getModifiedOn--) | احصل أو عيّن تاريخ تعديل التوقيع. |
| [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | احصل أو عيّن تاريخ تعديل التوقيع. |
| [getTop()](#getTop--) | يحدد الموضع العلوي للتوقيع. |
| [setTop(int value)](#setTop-int-) | يحدد الموضع العلوي للتوقيع. |
| [getLeft()](#getLeft--) | يحدد الموضع الأيسر للتوقيع. |
| [setLeft(int value)](#setLeft-int-) | يحدد الموضع الأيسر للتوقيع. |
| [getWidth()](#getWidth--) | يحدد عرض التوقيع. |
| [setWidth(int value)](#setWidth-int-) | يحدد عرض التوقيع. |
| [getHeight()](#getHeight--) | يحدد ارتفاع التوقيع. |
| [setHeight(int value)](#setHeight-int-) | يحدد ارتفاع التوقيع. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
| [toString()](#toString--) |  |
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


يحدد نوع التوقيع. التوقيع الرقمي سيحتوي على هذه الخاصية.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


يحدد الصفحة التي تم العثور على التوقيع فيها.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


يحدد الصفحة التي تم العثور على التوقيع فيها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


معرف توقيع فريد لتعديل التوقيع في المستند عبر طريقتي Update أو Delete. ستُضبط هذه الخاصية تلقائيًا بعد استدعاء طريقة Sign أو Search. إذا تم حفظ هذه الخاصية مسبقًا، يمكن تعيينها يدويًا للتلاعب بالتوقيع.

**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


احصل أو عيّن العلامة لتحديد ما إذا كان هذا المكوّن توقيعًا أم محتوى المستند. تُستخدم هذه الخاصية مع طريقة Update لتعيين العنصر كتوقيع (true) أو كعنصر مستند (false).

**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


احصل أو عيّن العلامة لتحديد ما إذا كان هذا المكوّن توقيعًا أم محتوى المستند. تُستخدم هذه الخاصية مع طريقة Update لتعيين العنصر كتوقيع (true) أو كعنصر مستند (false).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


احصل أو عيّن العلامة لتحديد ما إذا تم حذف هذا التوقيع من المستند. تُستخدم هذه الخاصية فقط لسجلات سجل تاريخ المستند للحفاظ على قائمة التواقيع المحذوفة.

**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


احصل أو عيّن تاريخ إنشاء التوقيع.

**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


احصل أو عيّن تاريخ إنشاء التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


احصل أو عيّن تاريخ تعديل التوقيع.

**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


احصل أو عيّن تاريخ تعديل التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


يحدد الموضع العلوي للتوقيع.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


يحدد الموضع العلوي للتوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


يحدد الموضع الأيسر للتوقيع.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


يحدد الموضع الأيسر للتوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحدد عرض التوقيع.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يحدد عرض التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحدد ارتفاع التوقيع.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يحدد ارتفاع التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


يستبدل طريقة Equals لمقارنة خصائص التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| توقيع | java.lang.Object | كائن التوقيع للمقارنة معه. |

**Returns:**
boolean - يُرجِع true إذا كان كائن التوقيع الممرّر من نفس النوع وجميع خصائصه مساوية لخصائص هذا الكائن.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز طريقة GetHashCode

**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
