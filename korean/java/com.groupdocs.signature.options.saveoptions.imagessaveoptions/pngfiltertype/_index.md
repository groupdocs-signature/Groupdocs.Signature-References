---
title: "PngFilterType"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PNG 이미지 필터 유형을 나타냅니다."
type: docs
weight: 21
url: /ko/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

PNG 이미지 필터 유형을 나타냅니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [None](#None) | null-filter는 이미지 데이터 행에 대해 필터링을 하지 않음을 의미합니다. |
|
|  | [Sub](#Sub) | sub filter는 이미지 데이터에 감산 필터링이 적용됨을 의미합니다. |
|
|  | [Up](#Up) | up filter는 행별 감산 필터가 적용됨을 의미합니다. |
|
|  | [Avg](#Avg) | avg filter는 이미지 데이터에 평균 필터가 적용됨을 의미합니다. |
|
|  | [Paeth](#Paeth) | 그 path predictor filter. |
|
|  | [Adaptive](#Adaptive) | Adaptive filtering은 저장 프로세스가 가장 적합한 필터를 선택함을 의미합니다. |
각 데이터 행에 대해.
|
### None {#None}
```
public static final int None
```


null-filter는 이미지 데이터 행에 대해 필터링을 하지 않음을 의미합니다.


### Sub {#Sub}
```
public static final int Sub
```


sub filter는 이미지 데이터에 감산 필터링이 적용됨을 의미합니다.


### Up {#Up}
```
public static final int Up
```


up filter는 행별 감산 필터가 적용됨을 의미합니다.


### Avg {#Avg}
```
public static final int Avg
```


avg filter는 이미지 데이터에 평균 필터가 적용됨을 의미합니다.


### Paeth {#Paeth}
```
public static final int Paeth
```


그 path predictor filter.


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


Adaptive filtering은 저장 프로세스가 가장 적합한 필터를 선택함을 의미합니다.
각 데이터 행에 대해. 최상의 압축, 가장 느린 실행 시간.


