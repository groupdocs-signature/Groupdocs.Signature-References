---
title: "TextSearchOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Metin imzaları için arama seçeneklerini temsil eder."
type: docs
weight: 18
url: /tr/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

Metin imzaları için arama seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | TextSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | TextSearchOptions sınıfının yeni bir örneğini metin değeriyle başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getText()](#getText--) | Aramada eşleşecek imza metnini belirtir. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Aramada eşleşecek imza metnini belirtir. |
|
|  | [getMatchType()](#getMatchType--) | Metin eşleşme türü aramasını alır veya ayarlar. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Metin eşleşme türü aramasını alır veya ayarlar. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Aranacak metin imzası uygulamasını belirtir. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | Aranacak metin imzası uygulamasını belirtir. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


TextSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
```


TextSearchOptions sınıfının yeni bir örneğini metin değeriyle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Metin imzasının Metnini ayarlar. |
|

### getText() {#getText--}
```
public final String getText()
```


Aramada eşleşecek imza metnini belirtir.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Aramada eşleşecek imza metnini belirtir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Metin eşleşme türü aramasını alır veya ayarlar.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Metin eşleşme türü aramasını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


Aranacak metin imzası uygulamasını belirtir.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


Aranacak metin imzası uygulamasını belirtir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

