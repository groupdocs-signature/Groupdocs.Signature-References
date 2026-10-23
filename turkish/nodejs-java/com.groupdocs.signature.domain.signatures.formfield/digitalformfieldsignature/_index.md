---
title: "DigitalFormFieldSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Pdf Belgeleri için dijital imza giriş form alanı özelliklerini içerir."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
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
| [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | PdfDigitalFormFieldSignature'ı önceden tanımlı adla oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSigned()](#getSigned--) | Form-field Signature'ın dijital sertifika ile imzalanıp imzalanmadığını gösteren yalnızca okuma özelliği. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | FormField Signature örneğini klonlar. |
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


PdfDigitalFormFieldSignature'ı önceden tanımlı adla oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Form alanı nesnesinin adı. |

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Form-field Signature'ın dijital sertifika ile imzalanıp imzalanmadığını gösteren yalnızca okuma özelliği.

**Returns:**
boolean
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imza | java.lang.Object | Karşılaştırılacak imza nesnesi. |

**Returns:**
boolean - Geçilen imza nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int - İmza hash kodu
### deepClone() {#deepClone--}
```
public Object deepClone()
```


FormField Signature örneğini klonlar.

**Returns:**
java.lang.Object - Kopyalanmış FormField Signature örneğini döndürür.
