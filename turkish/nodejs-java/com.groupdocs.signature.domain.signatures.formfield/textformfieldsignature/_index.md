---
title: "TextFormFieldSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Pdf Belgesi için metin giriş form alanı imza özelliklerini içerir."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Pdf Belgesi için metin giriş form alanı imza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | PdfTextFormFieldSignature'ı önceden tanımlı adla oluşturur. |
| [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | PdfTextFormFieldSignature'ı önceden tanımlı adla oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getText()](#getText--) | Form alanı metin girişinin metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Form alanı metin girişinin metnini alır veya ayarlar. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | FormField Signature örneğini klonlar. |
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


PdfTextFormFieldSignature'ı önceden tanımlı adla oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Form alanı nesnesinin adı. |

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


PdfTextFormFieldSignature'ı önceden tanımlı adla oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Form alanı nesnesinin adı. |
| metin | java.lang.String | Form alanı nesnesinin metni. |

### getText() {#getText--}
```
public final String getText()
```


Form alanı metin girişinin metnini alır veya ayarlar.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Form alanı metin girişinin metnini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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
