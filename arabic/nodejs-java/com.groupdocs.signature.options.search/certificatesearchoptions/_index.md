---
title: "CertificateSearchOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات البحث لتوقيعات بيانات شهادة التعريف."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

يمثل خيارات البحث لتوقيعات بيانات شهادة التعريف.

--------------------

 **Learn more** 

 *  
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CertificateSearchOptions()](#CertificateSearchOptions--) | يقوم بتهيئة نسخة جديدة من فئة TextSearchOptions بالقيم الافتراضية. |
| [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | يقوم بتهيئة نسخة جديدة من فئة TextSearchOptions بقيمة نصية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getText()](#getText--) | يحدد نص خاصية الشهادة للمطابقة أثناء البحث. |
| [setText(String value)](#setText-java.lang.String-) | يحدد نص خاصية الشهادة للمطابقة أثناء البحث. |
| [getMatchType()](#getMatchType--) | يحصل أو يضبط نوع مطابقة النص في البحث. |
| [setMatchType(int value)](#setMatchType-int-) | يحصل أو يضبط نوع مطابقة النص في البحث. |
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


يقوم بتهيئة نسخة جديدة من فئة TextSearchOptions بالقيم الافتراضية.

### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
```


يقوم بتهيئة نسخة جديدة من فئة TextSearchOptions بقيمة نصية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | java.lang.String | تعيين النص لتوقيع النص. |

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


يحصل أو يضبط نوع مطابقة النص في البحث.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


يحصل أو يضبط نوع مطابقة النص في البحث.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

