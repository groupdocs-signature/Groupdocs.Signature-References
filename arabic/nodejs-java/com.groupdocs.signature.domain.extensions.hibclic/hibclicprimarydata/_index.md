---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "فئة لتخزين البيانات الأولية لرمز التعريف المرخص من مجلس رموز شريط الرعاية الصحية HIBC."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

فئة لتخزين البيانات الأولية لـ HIBC (مجلس رموز الباركود لصناعة الرعاية الصحية) LIC (رمز التعريف المرخص).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | المُنشئ الافتراضي ctor() |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | يحدد تاريخ رمز تعريف الملصق. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | يحدد تاريخ رمز تعريف الملصق. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | يحدد رقم المنتج أو الكتالوج. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | يحدد رقم المنتج أو الكتالوج. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | يحدد معرف وحدة القياس. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | يحدد معرف وحدة القياس. |
| [deepClone()](#deepClone--) | يحصل على نسخة من هذا الكائن. |
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


يحدد تاريخ رمز تعريف الملصق. يجب أن يكون رمز تعريف الملصق سلسلة أبجدية رقمية مكوّنة من 4 رموز، مع كون الحرف الأول دائمًا حرفًا أبجديًا.

**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


يحدد تاريخ رمز تعريف الملصق. يجب أن يكون رمز تعريف الملصق سلسلة أبجدية رقمية مكوّنة من 4 رموز، مع كون الحرف الأول دائمًا حرفًا أبجديًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


يحدد رقم المنتج أو الكتالوج. يجب أن يكون رقم المنتج أو الكتالوج سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.

**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


يحدد رقم المنتج أو الكتالوج. يجب أن يكون رقم المنتج أو الكتالوج سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


يحدد معرف وحدة القياس. يجب أن يكون معرف وحدة القياس قيمة صحيحة من 0 إلى 9.

**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


يحدد معرف وحدة القياس. يجب أن يكون معرف وحدة القياس قيمة صحيحة من 0 إلى 9.

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
