---
title: "DigitalSearchOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Dijital imzalar araması için temel seçenekleri temsil eder"
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Dijital imzalar araması için temel seçenekleri temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DigitalSearchOptions()](#DigitalSearchOptions--) | Varsayılan değerlerle DigitalSearchOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getComments()](#getComments--) | Aranacak Digital imzanın yorumları. |
| [setComments(String value)](#setComments-java.lang.String-) | Aranacak Digital imzanın yorumları. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Aranacak Digital imzanın tarih ve saat aralığı. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Aranacak Digital imzanın tarih ve saat aralığı. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | Aranacak Dijital İmzanın tarih ve saat aralığı. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Aranacak Dijital İmzanın tarih ve saat aralığı. |
| [getSubjectName()](#getSubjectName--) | Boş olmayan değerler için aranacak sertifikanın ayırt edici konu adını belirtir. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Boş olmayan değerler için aranacak sertifikanın ayırt edici konu adını belirtir. |
| [getIssuerName()](#getIssuerName--) | Boş olmayan değerler için aranacak sertifika verenin ayırt edici adını belirtir. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Boş olmayan değerler için aranacak sertifika verenin ayırt edici adını belirtir. |
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Varsayılan değerlerle DigitalSearchOptions sınıfının yeni bir örneğini başlatır.

### getComments() {#getComments--}
```
public final String getComments()
```


Aranacak Digital imzanın yorumları.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Aranacak Digital imzanın yorumları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Aranacak Dijital imzanın tarih ve saat aralığı. Boş değer yok sayılacaktır.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Aranacak Dijital imzanın tarih ve saat aralığı. Boş değer yok sayılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Aranacak Dijital İmzanın tarih ve saat aralığı. Boş değer yok sayılacaktır.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Aranacak Dijital İmzanın tarih ve saat aralığı. Boş değer yok sayılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Boş olmayan değerler için aranacak sertifikanın ayırt edici konu adını belirtir.

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Boş olmayan değerler için aranacak sertifikanın ayırt edici konu adını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Boş olmayan değerler için aranacak sertifika verenin ayırt edici adını belirtir.

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Boş olmayan değerler için aranacak sertifika verenin ayırt edici adını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

