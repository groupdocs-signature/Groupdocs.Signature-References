---
title: "TextSignatureImplementation"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PDF 텍스트 서명에 대한 구현 유형을 지정합니다."
type: docs
weight: 32
url: /ko/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

PDF 텍스트 서명에 대한 구현 유형을 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Native](#Native) | 텍스트 서명은 문서 페이지의 기본 텍스트 객체로 표시됩니다. |
|
|  | [Image](#Image) | 텍스트 서명은 문서 페이지의 이미지 객체로 표시됩니다. |
|
|  | [Annotation](#Annotation) | 텍스트 서명은 PDF 페이지의 텍스트 주석 객체로 표시됩니다. |
|
|  | [Sticker](#Sticker) | 텍스트 서명은 PDF 페이지의 스티커 객체로 표시됩니다. |
|
|  | [FormField](#FormField) | 텍스트 서명은 지정된 양식 필드의 텍스트로 표시됩니다. |
|
|  | [Watermark](#Watermark) | 텍스트 서명은 문서 페이지의 워터마크로 표시됩니다. |
|
### Native {#Native}
```
public static final int Native
```


텍스트 서명은 문서 페이지의 기본 텍스트 객체로 표시됩니다.


### Image {#Image}
```
public static final int Image
```


텍스트 서명은 문서 페이지의 이미지 객체로 표시됩니다.


### Annotation {#Annotation}
```
public static final int Annotation
```


텍스트 서명은 PDF 페이지의 텍스트 주석 객체로 표시됩니다.
주석은 라이선스 버전에서만 표시됩니다.


### Sticker {#Sticker}
```
public static final int Sticker
```


텍스트 서명은 PDF 페이지의 스티커 객체로 표시됩니다.


### FormField {#FormField}
```
public static final int FormField
```


텍스트 서명은 지정된 양식 필드의 텍스트로 표시됩니다.
이 구현 유형은 TextSignOptions.Text만 사용할 수 있습니다,
TextSignOptions.FormTextFieldType 및 TextSignOptions.FormTextFieldTitle 옵션.


### Watermark {#Watermark}
```
public static final int Watermark
```


텍스트 서명은 문서 페이지의 워터마크로 표시됩니다.


