---
title: "CertificateSearchOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات البحث لتواقيع بيانات شهادة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

يمثل خيارات البحث لتواقيع بيانات شهادة.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [CertificateSearchOptions()](#CertificateSearchOptions--) | ينشئ مثيلاً جديدًا من فئة TextSearchOptions بالقيم الافتراضية. |
|
|  | [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | ينشئ مثيلاً جديدًا من فئة TextSearchOptions بقيمة نصية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يحدد نص خاصية الشهادة للمطابقة أثناء البحث. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يحدد نص خاصية الشهادة للمطابقة أثناء البحث. |
|
|  | [getMatchType()](#getMatchType--) | يحصل أو يضبط نوع مطابقة النص للبحث. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | يحصل أو يضبط نوع مطابقة النص للبحث. |
|
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


ينشئ مثيلاً جديدًا من فئة TextSearchOptions بالقيم الافتراضية.


### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
```


ينشئ مثيلاً جديدًا من فئة TextSearchOptions بقيمة نصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | تعيين نص توقيع النص. |
|

### getText() {#getText--}
```
public final String getText()
```


يحدد نص خاصية الشهادة للمطابقة أثناء البحث.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحدد نص خاصية الشهادة للمطابقة أثناء البحث.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


يحصل أو يضبط نوع مطابقة النص للبحث.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


يحصل أو يضبط نوع مطابقة النص للبحث.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

