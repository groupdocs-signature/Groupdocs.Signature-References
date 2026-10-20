---
title: "CertificateSearchOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Sertifika meta verisi imzaları için arama seçeneklerini temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

Sertifika meta verisi imzaları için arama seçeneklerini temsil eder.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [CertificateSearchOptions()](#CertificateSearchOptions--) | TextSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | TextSearchOptions sınıfının yeni bir örneğini metin değeriyle başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getText()](#getText--) | Aramada eşleşecek sertifika özelliği metnini belirtir. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Aramada eşleşecek sertifika özelliği metnini belirtir. |
|
|  | [getMatchType()](#getMatchType--) | Metin eşleşme türü aramasını alır veya ayarlar. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Metin eşleşme türü aramasını alır veya ayarlar. |
|
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


TextSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
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


Aramada eşleşecek sertifika özelliği metnini belirtir.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Aramada eşleşecek sertifika özelliği metnini belirtir.


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

