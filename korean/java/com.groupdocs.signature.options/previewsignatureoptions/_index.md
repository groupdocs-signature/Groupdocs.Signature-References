---
title: "PreviewSignatureOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "서명 미리보기 옵션을 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

서명 미리보기 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | PreviewSignatureOptions 객체를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | 서명을 구별하기 위한 고유 값입니다. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | 서명을 구별하기 위한 고유 값입니다. |
|
|  | [getSignOptions()](#getSignOptions--) | 미리보기를 생성하기 위한 서명 옵션입니다. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | 미리보기를 생성하기 위한 서명 옵션입니다. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | 미리보기 이미지 형식을 가져오거나 설정합니다. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | 미리보기 이미지 형식을 가져오거나 설정합니다. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


PreviewSignatureOptions 객체를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 미리보기를 생성할 서명 옵션입니다. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | 출력 페이지 미리보기 스트림을 생성하는 메서드를 정의하는 인터페이스입니다. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


서명을 구별하기 위한 고유 값입니다.
미리보기 옵션을 식별하려면 SignatureId를 사용합니다.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


서명을 구별하기 위한 고유 값입니다.
미리보기 옵션을 식별하려면 SignatureId를 사용합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


미리보기를 생성하기 위한 서명 옵션입니다.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


미리보기를 생성하기 위한 서명 옵션입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


미리보기 이미지 형식을 가져오거나 설정합니다.
기본값은 PNG입니다.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


미리보기 이미지 형식을 가져오거나 설정합니다.
기본값은 PNG입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

