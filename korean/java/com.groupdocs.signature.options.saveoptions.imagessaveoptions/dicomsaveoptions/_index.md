---
title: "DicomSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "DICOM 이미지 문서에 대한 저장 옵션."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

DICOM 이미지 문서에 대한 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | 기본값으로 DicomSaveOptions를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | DICOM용 XMP 데이터. |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | DICOM용 XMP 데이터. |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


기본값으로 DicomSaveOptions를 생성합니다.


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


DICOM용 XMP 데이터. 이미지 메타데이터 설정에 사용합니다.


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


DICOM용 XMP 데이터. 이미지 메타데이터 설정에 사용합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

