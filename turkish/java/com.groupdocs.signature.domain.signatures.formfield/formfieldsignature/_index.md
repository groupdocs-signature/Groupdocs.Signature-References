---
title: "FormFieldSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Form alanı imza özelliklerini içerir."
type: docs
weight: 13
url: /tr/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Form alanı imza özelliklerini içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Benzersiz form alanı adını belirtir. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Benzersiz form alanı adını belirtir. |
|
|  | [getType()](#getType--) | Form alanı tipini belirtir. |
|
|  | [getValue()](#getValue--) | Form alanı veri nesnesini belirtir. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Form alanı veri nesnesini belirtir. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | FormField Signature örneğini kopyalar. |
|
### getName() {#getName--}
```
public final String getName()
```


Benzersiz form alanı adını belirtir.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Benzersiz form alanı adını belirtir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Form alanı tipini belirtir.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Form alanı veri nesnesini belirtir.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Form alanı veri nesnesini belirtir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

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

