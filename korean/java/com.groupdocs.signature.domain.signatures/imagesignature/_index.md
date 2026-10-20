---
title: "ImageSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 서명 속성을 포함합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

이미지 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | 검색 프로세스 후에 얻은 서명 식별자를 사용하여 ImageSignature 객체를 초기화합니다. |
|
|  | [ImageSignature()](#ImageSignature--) | 기본 매개변수로 ImageSignature를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSize()](#getSize--) | 서명 이미지의 바이트 크기를 지정합니다. |
|
|  | [setSize(int value)](#setSize-int-) | 서명 이미지의 바이트 크기를 지정합니다. |
|
|  | [getFormat()](#getFormat--) | 서명 이미지의 형식을 지정합니다. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | 서명 이미지의 형식을 지정합니다. |
|
|  | [getContent()](#getContent--) | 형식의 이미지 바이너리 데이터 내용을 지정합니다. |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | Barcode Signature 인스턴스를 복제합니다. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


검색 프로세스 후에 얻은 서명 식별자를 사용하여 ImageSignature 객체를 초기화합니다.
이 고유 식별자는 문서 서명 정보 레이어에서 이 서명의 추가 속성을 찾는 데 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatureId | java.lang.String | Signature 클래스의 Sign 또는 Search 메서드로 얻은 고유 서명 식별자 [Signature](../../com.groupdocs.signature/signature). |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


기본 매개변수로 ImageSignature를 초기화합니다.


### getSize() {#getSize--}
```
public final int getSize()
```


서명 이미지의 바이트 크기를 지정합니다.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


서명 이미지의 바이트 크기를 지정합니다.



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


서명 이미지의 형식을 지정합니다.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


서명 이미지의 형식을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


형식의 이미지 바이너리 데이터 내용을 지정합니다.
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
기본적으로 이 속성은 설정되지 않습니다.
속성 사용
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) 이 기능을 활성화합니다.


**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 서명 | java.lang.Object | 비교할 서명 객체. |
|

**Returns:**
boolean - 전달된 서명 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int - 서명 해시 코드

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Barcode Signature 인스턴스를 복제합니다.


**Returns:**
java.lang.Object - 복제된 바코드 서명 인스턴스를 반환합니다.

