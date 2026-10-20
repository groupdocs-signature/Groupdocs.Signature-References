---
title: "ComboboxFormFieldSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Açılır kutu giriş form alanı imza özelliklerini içerir."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Açılır kutu giriş form alanı imza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Önceden tanımlı adla ComboboxFormFieldSignature oluşturur. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Önceden tanımlı ad ve seçenekler listesiyle ComboboxFormFieldSignature oluşturur. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Önceden tanımlı ad, seçenekler listesi ve seçili değerle ComboboxFormFieldSignature oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSelected()](#getSelected--) | Seçili değeri al veya ayarla. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Seçili değeri al veya ayarla. |
|
|  | [getItems()](#getItems--) | Combo-box seçenekler listesini al veya ayarla. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Combo-box seçenekler listesini al veya ayarla. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | FormField Signature örneğini kopyalar. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Önceden tanımlı adla ComboboxFormFieldSignature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Form alanı nesnesinin adı. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Önceden tanımlı ad ve seçenekler listesiyle ComboboxFormFieldSignature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Form alanı nesnesinin adı. |
|
|  | items | java.util.List<java.lang.String> | Combo-box listesinin değerleri. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Önceden tanımlı ad, seçenekler listesi ve seçili değerle ComboboxFormFieldSignature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Form alanı nesnesinin adı. |
|
|  | items | java.util.List<java.lang.String> | Combo-box listesinin değerleri. |
|
|  | selected | java.lang.Object | Seçili değer. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Seçili değeri al veya ayarla.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Seçili değeri al veya ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Combo-box seçenekler listesini al veya ayarla.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Combo-box seçenekler listesini al veya ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<java.lang.String> |  |

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

