---
title: "TextSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Metin imza özelliklerini içerir."
type: docs
weight: 18
url: /tr/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Metin imza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Arama işleminden sonra elde edilen imza tanımlayıcısı ile TextSignature nesnesini başlat. |
|
| [TextSignature()](#TextSignature--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getText()](#getText--) | İmzada metni belirtir. |
|
|  | [setText(String value)](#setText-java.lang.String-) | İmzada metni belirtir. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Metin imza uygulamasını belirtir. |
|
|  | [getNative()](#getNative--) | Yerel özelliği belirtir. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Yerel özelliği belirtir. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | Metin İmzası örneğini klonlayın. |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Arama işleminden sonra elde edilen imza tanımlayıcısı ile TextSignature nesnesini başlat.
Bu benzersiz tanımlayıcı, bu imzanın ek özelliklerini belge imza bilgi katmanından bulmak için kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatureId | java.lang.String | İmza veya arama yöntemiyle elde edilen benzersiz imza tanımlayıcısı. |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


İmzada metni belirtir.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


İmzada metni belirtir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Metin imza uygulamasını belirtir.


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Yerel özelliği belirtir. İmza belgeye özgü ise doğru (true) olur.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Yerel özelliği belirtir. İmza belgeye özgü ise doğru (true) olur.


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


Metin İmzası örneğini klonlayın.


**Returns:**
java.lang.Object - Klonlanmış Metin İmzası örneğini döndürür.

