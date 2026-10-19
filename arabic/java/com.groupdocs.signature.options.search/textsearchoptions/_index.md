---
title: "TextSearchOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات البحث لتواقيع النص."
type: docs
weight: 18
url: /ar/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

يمثل خيارات البحث لتواقيع النص.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | ينشئ مثيلاً جديدًا من فئة TextSearchOptions بالقيم الافتراضية. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | ينشئ مثيلاً جديدًا من فئة TextSearchOptions بقيمة نصية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يحدد نص التوقيع للمطابقة أثناء البحث. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يحدد نص التوقيع للمطابقة أثناء البحث. |
|
|  | [getMatchType()](#getMatchType--) | يحصل أو يضبط نوع مطابقة النص للبحث. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | يحصل أو يضبط نوع مطابقة النص للبحث. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | يحدد تنفيذ توقيع النص للبحث. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | يحدد تنفيذ توقيع النص للبحث. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


ينشئ مثيلاً جديدًا من فئة TextSearchOptions بالقيم الافتراضية.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
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


يحدد نص التوقيع للمطابقة أثناء البحث.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحدد نص التوقيع للمطابقة أثناء البحث.


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


يحدد تنفيذ توقيع النص للبحث.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


يحدد تنفيذ توقيع النص للبحث.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

