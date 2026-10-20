---
title: "BarcodeSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "바코드 서명 속성을 포함합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

바코드 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | 검색 과정 후에 얻은 서명 식별자를 사용하여 BarcodeSignature 객체를 초기화합니다. |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | 기본 매개변수로 BarcodeSignature를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Barcode 인코드 유형을 지정합니다. |
|
|  | [getText()](#getText--) | Barcode의 텍스트를 지정합니다. |
|
|  | [getFormat()](#getFormat--) | Barcode 서명 이미지의 형식을 지정합니다. |
|
|  | [getContent()](#getContent--) | Barcode 이진 데이터 이미지 콘텐츠의 유형을 지정합니다. |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | Barcode Signature 인스턴스를 복제합니다. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


검색 과정 후에 얻은 서명 식별자를 사용하여 BarcodeSignature 객체를 초기화합니다.
이 고유 식별자는 문서 서명 정보 레이어에서 이 서명의 추가 속성을 찾는 데 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatureId | java.lang.String | Signature 클래스의 Sign 또는 Search 메서드로 얻은 고유 서명 식별자 [Signature](../../com.groupdocs.signature/signature). |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


기본 매개변수로 BarcodeSignature를 초기화합니다.


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barcode 인코드 유형을 지정합니다.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Barcode의 텍스트를 지정합니다.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Barcode 서명 이미지의 형식을 지정합니다.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Barcode 이진 데이터 이미지 콘텐츠의 유형을 지정합니다.
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
기본적으로 이 속성은 설정되지 않습니다.
속성 사용
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) 이 기능을 활성화하려면.


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

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| 이미지 | java.awt.image.BufferedImage |  |

