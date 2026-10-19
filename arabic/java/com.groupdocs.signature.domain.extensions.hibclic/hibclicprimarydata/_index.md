---
title: "HIBCLICPrimaryData"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "فئة لتخزين البيانات الأولية لـ HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

فئة لتخزين البيانات الأولية لـ HIBC (مجلس رموز الباركود في صناعة الرعاية الصحية) LIC (رمز التعريف المرخص).

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | المُنشئ الافتراضي ctor() |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | يحدد تاريخ رمز تعريف الملصق. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | يحدد تاريخ رمز تعريف الملصق. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | يحدد رقم المنتج أو رقم الكتالوج. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | يحدد رقم المنتج أو رقم الكتالوج. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | يحدد معرف وحدة القياس. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | يحدد معرف وحدة القياس. |
|
|  | [deepClone()](#deepClone--) | يحصل على نسخة من هذا الكائن. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


المُنشئ الافتراضي ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


يحدد تاريخ رمز تعريف الملصق. يجب أن يكون رمز تعريف الملصق
سلسلة مكوّنة من 4 رموز أبجدية رقمية، بحيث يكون الحرف الأول دائمًا حرفًا أبجديًا.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


يحدد تاريخ رمز تعريف الملصق. يجب أن يكون رمز تعريف الملصق
سلسلة مكوّنة من 4 رموز أبجدية رقمية، بحيث يكون الحرف الأول دائمًا حرفًا أبجديًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


يحدد رقم المنتج أو رقم الكتالوج. يجب أن يكون رقم المنتج أو رقم الكتالوج أبجدياً رقمياً
سلسلة بطول يصل إلى 18 رمزًا.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


يحدد رقم المنتج أو رقم الكتالوج. يجب أن يكون رقم المنتج أو رقم الكتالوج أبجدياً رقمياً
سلسلة بطول يصل إلى 18 رمزًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


يحدد معرف وحدة القياس. يجب أن يكون معرف وحدة القياس قيمة عددية صحيحة من 0 إلى 9.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


يحدد معرف وحدة القياس. يجب أن يكون معرف وحدة القياس قيمة عددية صحيحة من 0 إلى 9.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


يحصل على نسخة من هذا الكائن.


**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
