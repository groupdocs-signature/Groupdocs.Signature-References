---
title: "HIBCLICSecondaryAdditionalData"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "فئة لتخزين البيانات الثانوية والإضافية لرمز التعريف المرخص من مجلس رموز شريط الرعاية الصحية HIBC."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

فئة لتخزين بيانات HIBC (مجلس قطاع الرعاية الصحية للباركود) LIC (رمز التعريف المرخص) الثانوية والإضافية.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | المُنشئ الافتراضي ctor() |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | يحدد تنسيق تاريخ الانتهاء. |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | يحدد تنسيق تاريخ الانتهاء. |
|
|  | [getExpiryDate()](#getExpiryDate--) | يحدد تاريخ الانتهاء. |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | يحدد تاريخ الانتهاء. |
|
|  | [getLotNumber()](#getLotNumber--) | يحدد رقم اللوت أو رقم الدفعة. |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | يحدد رقم اللوت أو رقم الدفعة. |
|
|  | [getSerialNumber()](#getSerialNumber--) | يحدد الرقم التسلسلي. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | يحدد الرقم التسلسلي. |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | يحدد تاريخ الصنع. |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | يحدد تاريخ الصنع. |
|
|  | [getQuantity()](#getQuantity--) | يحدد الكمية، يجب أن تكون قيمة عددية صحيحة من 0 إلى 500. |
|
|  | [setQuantity(int value)](#setQuantity-int-) | يحدد الكمية، يجب أن تكون قيمة عددية صحيحة من 0 إلى 500. |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | يحدد حرف الرابط في سلسلة الإخراج. |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | يحدد حرف الرابط في سلسلة الإخراج. |
|
|  | [deepClone()](#deepClone--) | يحصل على نسخة من هذا الكائن. |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


المُنشئ الافتراضي ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


يحدد تنسيق تاريخ الانتهاء.


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


يحدد تنسيق تاريخ الانتهاء.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم تعيين ExpiryDateFormat إلى None.


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم تعيين ExpiryDateFormat إلى None.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


يحدد رقم اللوت أو رقم الدفعة.
يجب أن يكون رقم الدفعة/اللوت سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


يحدد رقم اللوت أو رقم الدفعة.
يجب أن يكون رقم الدفعة/اللوت سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


يحدد الرقم التسلسلي.
يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


يحدد الرقم التسلسلي.
يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


يحدد تاريخ الصنع.
يمكن تعيين تاريخ الصنع إلى DateTime.MinValue لتجنب استخدام هذا الحقل.
القيمة الافتراضية: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


يحدد تاريخ الصنع.
يمكن تعيين تاريخ الصنع إلى DateTime.MinValue لتجنب استخدام هذا الحقل.
القيمة الافتراضية: DateTime.MinValue


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


يحدد الكمية، يجب أن تكون قيمة عددية صحيحة من 0 إلى 500.
يمكن تعيين الكمية إلى -1 لتجنب استخدام هذا الحقل. القيمة الافتراضية: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


يحدد الكمية، يجب أن تكون قيمة عددية صحيحة من 0 إلى 500.
يمكن تعيين الكمية إلى -1 لتجنب استخدام هذا الحقل. القيمة الافتراضية: -1


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


يحدد حرف الرابط في سلسلة الإخراج.


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


يحدد حرف الرابط في سلسلة الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


يحصل على نسخة من هذا الكائن.


**Returns:**
java.lang.Object
