---
title: "DigitalFormFieldSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Pdf Belgeleri için dijital imza giriş form alanı özelliklerini içerir."
type: docs
weight: 12
url: /tr/java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Pdf Belgeleri için dijital imza giriş form alanı özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | Önceden tanımlı adla PdfDigitalFormFieldSignature oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSigned()](#getSigned--) | Form-field Signature'ın dijital sertifika ile imzalanıp imzalanmadığını gösteren yalnızca okunabilir özellik. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | FormField Signature örneğini kopyalar. |
|
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


Önceden tanımlı adla PdfDigitalFormFieldSignature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Form alanı nesnesinin adı. |
|

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Form-field Signature'ın dijital sertifika ile imzalanıp imzalanmadığını gösteren yalnızca okunabilir özellik.


**Returns:**
boolean
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

