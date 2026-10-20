---
title: "TextVerifyOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belge Metin imzasını doğrulama seçeneklerini tutar."
type: docs
weight: 14
url: /tr/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Belge Metin imzasını doğrulama seçeneklerini tutar.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | TextVerifyOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | TextVerifyOptions sınıfının yeni bir örneğini doğrulama metniyle başlatır. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | TextVerifyOptions sınıfının yeni bir örneğini doğrulanacak Metin özelliği ve imza uygulamasıyla başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getText()](#getText--) | Doğrulanması gerekiyorsa İmza Metnini belirtin. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Doğrulanması gerekiyorsa İmza Metnini belirtin. |
|
|  | [getMatchType()](#getMatchType--) | Metin Eşleşme Türü doğrulamasını alır veya ayarlar. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Metin Eşleşme Türü doğrulamasını alır veya ayarlar. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Doğrulanacak İmzanın türü. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Doğrulanacak İmzanın türü. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Doğrulanacak form alanının başlığını alır veya ayarlar. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Doğrulanacak form alanının başlığını alır veya ayarlar. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Doğrulanacak form alanının türünü alır veya ayarlar. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Doğrulanacak form alanının türünü alır veya ayarlar. |
|
|  | [getSignatureID()](#getSignatureID--) | Doğrulanması gerekiyorsa Metin İmza Kimliğini sıfırdan büyük olarak belirtin. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Doğrulanması gerekiyorsa Metin İmza Kimliğini sıfırdan büyük olarak belirtin. |
|
|  | [toString()](#toString--) | Stringe dönüşümü geçersiz kılar. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


TextVerifyOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


TextVerifyOptions sınıfının yeni bir örneğini doğrulama metniyle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Doğrulanacak metin |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


TextVerifyOptions sınıfının yeni bir örneğini doğrulanacak Metin özelliği ve imza uygulamasıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Doğrulanacak metin. |
|
|  | uygulama | int | İmza Uygulama türü. |
|

### getText() {#getText--}
```
public final String getText()
```


Doğrulanması gerekiyorsa İmza Metnini belirtin.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Doğrulanması gerekiyorsa İmza Metnini belirtin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Metin Eşleşme Türü doğrulamasını alır veya ayarlar.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Metin Eşleşme Türü doğrulamasını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Doğrulanacak İmzanın türü.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Doğrulanacak İmzanın türü.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Doğrulanacak form alanının başlığını alır veya ayarlar.
Bu özellik ayar metni yalnızca metin form alanlarında bulunur.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Doğrulanacak form alanının başlığını alır veya ayarlar.
Bu özellik ayar metni yalnızca metin form alanlarında bulunur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Doğrulanacak form alanının türünü alır veya ayarlar.
Bu özellik ayar metni yalnızca metin form alanlarında bulunur.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Doğrulanacak form alanının türünü alır veya ayarlar.
Bu özellik ayar metni yalnızca metin form alanlarında bulunur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Doğrulanacaksa Metin İmzası Kimliğini sıfırdan büyük olarak belirtin. Bu özellik yalnızca PDF belgeleri için desteklenir.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Doğrulanacaksa Metin İmzası Kimliğini sıfırdan büyük olarak belirtin. Bu özellik yalnızca PDF belgeleri için desteklenir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```


Stringe dönüşümü geçersiz kılar.


**Returns:**
java.lang.String -
