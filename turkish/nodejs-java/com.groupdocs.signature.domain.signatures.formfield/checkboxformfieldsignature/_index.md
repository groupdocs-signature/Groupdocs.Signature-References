---
title: "CheckboxFormFieldSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Check-box giriş form alanı imza özelliklerini içerir."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Check-box giriş form alanı imza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Önceden tanımlı adla PdfCheckboxFormFieldSignature oluşturur. |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Önceden tanımlı ad ve değerle PdfCheckboxFormFieldSignature oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChecked()](#getChecked--) | Form alanı onay kutusu girişinin işaretli değerini alır veya ayarlar. |
| [setChecked(boolean value)](#setChecked-boolean-) | Form alanı onay kutusu girişinin işaretli değerini alır veya ayarlar. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | FormField Signature örneğini klonlar. |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Önceden tanımlı adla PdfCheckboxFormFieldSignature oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Form alanı nesnesinin adı. |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Önceden tanımlı ad ve değerle PdfCheckboxFormFieldSignature oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Form alanı nesnesinin adı. |
| isChecked | boolean | Onay kutusu işaretli ise değer |

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
