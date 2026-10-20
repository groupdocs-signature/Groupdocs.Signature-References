---
title: "StampTypes"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "스탬프 유형 컨테이너."
type: docs
weight: 16
url: /ko/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

스탬프 유형 컨테이너.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Round](#Round) | 원형 스탬프 유형 객체. |
|
|  | [Square](#Square) | 사각형 스탬프 유형 객체. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | 모든 스탬프 유형. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | pasringType 이름을 가진 스탬프 유형을 반환합니다. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType 이름을 가진 스탬프 유형을 반환합니다. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


원형 스탬프 유형 객체.


### Square {#Square}
```
public static final StampType Square
```


사각형 스탬프 유형 객체.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


모든 스탬프 유형.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


pasringType 이름을 가진 스탬프 유형을 반환합니다. 스탬프 이름을 알 수 없을 경우 - 예외가 발생합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | parsingType | java.lang.String | 스탬프 유형 이름의 원본 문자열. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


pasringType 이름을 가진 스탬프 유형을 반환합니다. 스탬프 이름을 알 수 없을 경우 - 예외가 발생하지 않으며 메서드는 null 값을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | parsingType | java.lang.String | 스탬프 유형 이름의 원본 문자열. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

