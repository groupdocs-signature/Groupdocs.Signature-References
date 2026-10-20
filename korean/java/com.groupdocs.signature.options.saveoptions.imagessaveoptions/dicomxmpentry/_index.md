---
title: "DicomXmpEntry"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "DICOM 이미지(.dcm)를 위한 XMP 데이터 항목."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

DICOM 이미지(.dcm)의 XMP 데이터 입력.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | DICOM 이미지에 대한 XMP 항목을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getType()](#getType--) | 항목 유형. |
|
|  | [getValue()](#getValue--) | 항목 값. |
|
|  | [toString()](#toString--) | XMP 항목의 텍스트 표현을 가져옵니다. |
|
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


DICOM 이미지에 대한 XMP 항목을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 유형 | int | 항목 유형 |
|
|  | 값 | java.lang.String | 항목 값 |
|

### getType() {#getType--}
```
public final int getType()
```


항목 유형.


**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


항목 값.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


XMP 항목의 텍스트 표현을 가져옵니다.


**Returns:**
java.lang.String - XMP 항목 텍스트 표현.

