---
title: "TextureBrush"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "텍스처 브러시를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

텍스처 브러시를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | TextureBrush 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | TextureBrush 클래스의 새 인스턴스를 이미지 파일로 초기화합니다. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | TextureBrush 클래스의 새 인스턴스를 이미지 스트림 옵션으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | 텍스처 이미지 파일 경로를 가져오거나 설정합니다. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | 텍스처 이미지 파일 경로를 가져오거나 설정합니다. |
|
|  | [getImageStream()](#getImageStream--) | 텍스처 이미지 스트림을 가져오거나 설정합니다. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | 텍스처 이미지 스트림을 가져오거나 설정합니다. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


TextureBrush 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


TextureBrush 클래스의 새 인스턴스를 이미지 파일로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | 이미지 파일 경로. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


TextureBrush 클래스의 새 인스턴스를 이미지 스트림 옵션으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | 이미지 스트림. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


텍스처 이미지 파일 경로를 가져오거나 설정합니다.
이 속성은 ImageStream이 지정되지 않은 경우에만 사용됩니다.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


텍스처 이미지 파일 경로를 가져오거나 설정합니다.
이 속성은 ImageStream이 지정되지 않은 경우에만 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


텍스처 이미지 스트림을 가져오거나 설정합니다.
이 속성이 지정되면 항상 ImageFilePath 대신 사용됩니다.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


텍스처 이미지 스트림을 가져오거나 설정합니다.
이 속성이 지정되면 항상 ImageFilePath 대신 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.io.InputStream |  |

