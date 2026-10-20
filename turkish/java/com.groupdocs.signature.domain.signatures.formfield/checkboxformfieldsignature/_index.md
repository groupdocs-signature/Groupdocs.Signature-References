---
title: "CheckboxFormFieldSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Onay kutusu giriş form alanı imza özelliklerini içerir."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Onay kutusu giriş form alanı imza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | PdfCheckboxFormFieldSignature'ı önceden tanımlı adla oluşturur. |
|
|  | [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | PdfCheckboxFormFieldSignature'ı önceden tanımlı ad ve değerle oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getChecked()](#getChecked--) | Form alanı onay kutusu girişinin işaretli değerini alır veya ayarlar. |
|
|  | [setChecked(boolean value)](#setChecked-boolean-) | Form alanı onay kutusu girişinin işaretli değerini alır veya ayarlar. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | FormField Signature örneğini kopyalar. |
|
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


PdfCheckboxFormFieldSignature'ı önceden tanımlı adla oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Form alanı nesnesinin adı. |
|

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


PdfCheckboxFormFieldSignature'ı önceden tanımlı ad ve değerle oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Form alanı nesnesinin adı. |
|
|  | isChecked | boolean | Onay kutusu işaretli ise değer |
|

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Form alanı onay kutusu girişinin işaretli değerini alır veya ayarlar.


**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Form alanı onay kutusu girişinin işaretli değerini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imza | java.lang.Object | Karşılaştırılacak imza nesnesi. |
|

**Returns:**
boolean - Geçilen imza nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode yöntemini geçersiz kılar


**Returns:**
int - İmza karma kodu

### deepClone() {#deepClone--}
```
public Object deepClone()
```


FormField Signature örneğini kopyalar.


**Returns:**
java.lang.Object - Kopyalanmış FormField Signature örneğini döndürür.

