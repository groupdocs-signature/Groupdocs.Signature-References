---
title: "SpreadsheetPosition"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "스프레드시트 문서용 서명 위치를 정의합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.domain.extensions.signoptions/spreadsheetposition/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class SpreadsheetPosition extends SignatureExtension
```

스프레드시트 문서용 서명 위치를 정의합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetPosition(int row, int column)](#SpreadsheetPosition-int-int-) | 미리 정의된 행과 열을 사용하여 스프레드시트 서명 위치를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getRow()](#getRow--) | 서명의 상단 행 번호를 가져오거나 설정합니다 (최소값은 0). |
|
|  | [setRow(int value)](#setRow-int-) | 서명의 상단 행 번호를 가져오거나 설정합니다 (최소값은 0). |
|
|  | [getColumn()](#getColumn--) | 서명의 왼쪽 열 번호를 가져오거나 설정합니다 (최소값은 0). |
|
|  | [setColumn(int value)](#setColumn-int-) | 서명의 왼쪽 열 번호를 가져오거나 설정합니다 (최소값은 0). |
|
### SpreadsheetPosition(int row, int column) {#SpreadsheetPosition-int-int-}
```
public SpreadsheetPosition(int row, int column)
```


미리 정의된 행과 열을 사용하여 스프레드시트 서명 위치를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 행 | int |  |
| 열 | int |  |

### getRow() {#getRow--}
```
public final int getRow()
```


서명의 상단 행 번호를 가져오거나 설정합니다 (최소값은 0).


**Returns:**
int
### setRow(int value) {#setRow-int-}
```
public final void setRow(int value)
```


서명의 상단 행 번호를 가져오거나 설정합니다 (최소값은 0).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getColumn() {#getColumn--}
```
public final int getColumn()
```


서명의 왼쪽 열 번호를 가져오거나 설정합니다 (최소값은 0).


**Returns:**
int
### setColumn(int value) {#setColumn-int-}
```
public final void setColumn(int value)
```


서명의 왼쪽 열 번호를 가져오거나 설정합니다 (최소값은 0).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

