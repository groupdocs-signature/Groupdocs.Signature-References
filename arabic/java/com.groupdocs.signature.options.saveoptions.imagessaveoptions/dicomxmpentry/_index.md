---
title: "DicomXmpEntry"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "إدخال بيانات XMP لصور DICOM .dcm."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

إدخال بيانات XMP لصور DICOM (.dcm).

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | ينشئ إدخال Xmp لصورة DICOM. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getType()](#getType--) | نوع الإدخال. |
|
|  | [getValue()](#getValue--) | قيمة الإدخال. |
|
|  | [toString()](#toString--) | احصل على تمثيل نصي لإدخال Xmp. |
|
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


ينشئ إدخال Xmp لصورة DICOM.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نوع | int | نوع الإدخال |
|
|  | قيمة | java.lang.String | قيمة الإدخال |
|

### getType() {#getType--}
```
public final int getType()
```


نوع الإدخال.


**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


قيمة الإدخال.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


احصل على تمثيل نصي لإدخال Xmp.


**Returns:**
java.lang.String - تمثيل نصي لإدخال Xmp.

