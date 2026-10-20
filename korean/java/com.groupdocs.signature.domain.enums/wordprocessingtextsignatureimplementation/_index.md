---
title: "WordProcessingTextSignatureImplementation"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "WordProcessing 문서에 대한 텍스트 서명 구현 유형을 지정합니다."
type: docs
weight: 36
url: /ko/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

WordProcessing 문서에 대한 텍스트 서명 구현 유형을 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [TextStamp](#TextStamp) | Words 페이지에 레이블 객체로 표시된 �스트 서명. |
|
|  | [TextAsImage](#TextAsImage) | Words 페이지에 이미지 객체로 표시된 텍스트 서명. |
|
|  | [TextToFormField](#TextToFormField) | 텍스트 서명은 지정된 양식 필드의 텍스트로 표시됩니다. |
|
|  | [Watermark](#Watermark) | Words 페이지에 워터마크로 표시된 텍스트 서명. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Words 페이지에 레이블 객체로 표시된 �스트 서명.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Words 페이지에 이미지 객체로 표시된 텍스트 서명.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


텍스트 서명은 지정된 양식 필드의 텍스트로 표시됩니다.
이 구현 유형은 TextSignOptions.Text만 사용할 수 있습니다,
TextSignOptions.FormTextFieldTitle 및 TextSignOptions.FormTextFieldType 옵션.


### Watermark {#Watermark}
```
public static final int Watermark
```


Words 페이지에 워터마크로 표시된 텍스트 서명.


