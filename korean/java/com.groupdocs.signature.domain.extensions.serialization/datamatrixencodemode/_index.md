---
title: "DataMatrixEncodeMode"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "DataMatrix 인코더의 인코딩 모드는 기본값이 Auto입니다"
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

DataMatrix 인코더의 인코딩 모드, 기본값은 자동입니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Auto](#Auto) | DataMatrix 인코딩에 대해 최적의 인코드 모드를 자동으로 선택합니다 |
|
|  | [ASCII](#ASCII) | 바이트당 알파벳 또는 숫자 문자 하나, 혹은 숫자 두 개를 인코딩합니다 |
|
|  | [Full](#Full) | 8비트 값을 인코딩합니다 |
|
|  | [Custom](#Custom) | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding에 지정된 인코딩으로 인코딩합니다 |
|
|  | [C40](#C40) | C40 인코딩을 사용합니다. |
|
|  | [Text](#Text) | 텍스트 인코딩을 사용합니다. |
|
|  | [EDIFACT](#EDIFACT) | EDIFACT 인코딩을 사용합니다. |
|
|  | [ANSIX12](#ANSIX12) | ANSI X12 인코딩을 사용합니다. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | ExtendedCodetext 모드를 사용하면 코드-텍스트에서 인코딩 방식을 수동으로 전환할 수 있습니다. |
|
### Auto {#Auto}
```
public static final int Auto
```


DataMatrix 인코딩에 대해 최적의 인코드 모드를 자동으로 선택합니다


### ASCII {#ASCII}
```
public static final int ASCII
```


바이트당 알파벳 또는 숫자 문자 하나, 혹은 숫자 두 개를 인코딩합니다


### Full {#Full}
```
public static final int Full
```


8비트 값을 인코딩합니다


### Custom {#Custom}
```
public static final int Custom
```


BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding에 지정된 인코딩으로 인코딩합니다


### C40 {#C40}
```
public static final int C40
```


C40 인코딩을 사용합니다. 대문자 알파벳-숫자, 소문자 및 특수 문자를 인코딩합니다.


### Text {#Text}
```
public static final int Text
```


텍스트 인코딩을 사용합니다. 소문자 알파벳-숫자, 대문자 및 특수 문자를 인코딩합니다.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


EDIFACT 인코딩을 사용합니다. 문자당 6비트를 사용하며, 숫자를 인코딩합니다,
대문자와 많은 구두점을 인코딩하지만, 소문자는 지원하지 않습니다.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


ANSI X12 인코딩을 사용합니다.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


ExtendedCodetext 모드를 사용하면 코드-텍스트에서 인코딩 방식을 수동으로 전환할 수 있습니다.
형식 : "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
허용되는 인코딩 스킴은 다음과 같습니다: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
확장 코드-텍스트 예시: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
두 배\\edifact:EdifactEncodedText"
텍스트에서 모든 백슬래시 (\\)는 두 번 사용해야 합니다.


