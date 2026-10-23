---
title: "ComboboxFormFieldSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Combo-box giriş form alanı imza özelliklerini içerir."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Combo-box giriş form alanı imza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | ComboboxFormFieldSignature'ı önceden tanımlı adla oluşturur. |
| [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | ComboboxFormFieldSignature'ı önceden tanımlı ad ve seçenek listesiyle oluşturur. |
| [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | ComboboxFormFieldSignature'ı önceden tanımlı ad, seçenek listesi ve seçili değerle oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSelected()](#getSelected--) | Seçili değeri al veya ayarla. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Seçili değeri al veya ayarla. |
| [getItems()](#getItems--) | Combo-box seçenek listesini al veya ayarla. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Combo-box seçenek listesini al veya ayarla. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | FormField Signature örneğini klonlar. |
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


ComboboxFormFieldSignature'ı önceden tanımlı adla oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Form alanı nesnesinin adı. |

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


ComboboxFormFieldSignature'ı önceden tanımlı ad ve seçenek listesiyle oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Form alanı nesnesinin adı. |
| items | java.util.List<java.lang.String> | Combo-box listesinin değerleri. |

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


ComboboxFormFieldSignature'ı önceden tanımlı ad, seçenek listesi ve seçili değerle oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Form alanı nesnesinin adı. |
| items | java.util.List<java.lang.String> | Combo-box listesinin değerleri. |
| selected | java.lang.Object | Seçili değer. |

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


Combo-box seçenek listesini al veya ayarla.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Combo-box seçenek listesini al veya ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<java.lang.String> |  |

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
