---
title: "DicomXmpEntry"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "DICOM görüntüleri .dcm için XMP veri girişi."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

DICOM görüntüleri (.dcm) için XMP veri girişi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | Bir DICOM görüntüsü için XMP girişi oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Giriş türü. |
| [getValue()](#getValue--) | Giriş değeri. |
| [toString()](#toString--) | XMP girişinin metinsel temsilini al. |
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


Bir DICOM görüntüsü için XMP girişi oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Giriş türü |
| değer | java.lang.String | Giriş değeri |

### getType() {#getType--}
```
public final int getType()
```


Giriş türü.

**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


Giriş değeri.

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


XMP girişinin metinsel temsilini al.

**Returns:**
java.lang.String - XMP girişinin metinsel temsili.
