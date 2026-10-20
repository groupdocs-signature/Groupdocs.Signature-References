---
title: "MetadataSignatureCollection"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "메타데이터 서명 객체의 컬렉션입니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

메타데이터 서명 객체의 컬렉션입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Metadata 서명 컬렉션을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCount()](#getCount--) | 컬렉션의 항목 수를 가져옵니다. |
|
|  | [clear()](#clear--) | 컬렉션의 모든 항목을 제거합니다. |
|
|  | [contains(String name)](#contains-java.lang.String-) | 컬렉션에 지정된 이름을 가진 Metadata가 존재하면 true를 반환합니다. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | 이름으로 속성의 인덱스를 가져옵니다. |
|
|  | [remove(String name)](#remove-java.lang.String-) | 컬렉션에서 지정된 이름을 가진 Metadata 서명을 제거합니다. |
|
|  | [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 Metadata 서명을 제거합니다. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Metadata 서명 객체를 컬렉션에 추가합니다. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Metadata 서명 컬렉션을 추가합니다. |
|
|  | [deepClone()](#deepClone--) | Metadata Signature Items가 포함된 Clone Metadata Signature Collection 클래스를 복제합니다. |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Metadata 서명 컬렉션을 생성합니다.


### getCount() {#getCount--}
```
public final int getCount()
```


컬렉션의 항목 수를 가져옵니다.


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


컬렉션의 모든 항목을 제거합니다.


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


컬렉션에 지정된 이름을 가진 Metadata가 존재하면 true를 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | 속성의 대소문자를 구분하지 않는 이름입니다. |
|

**Returns:**
boolean - 컬렉션에 메타데이터가 존재하면 true, 그렇지 않으면 false.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


이름으로 속성의 인덱스를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | MetadataSignature의 대소문자를 구분하지 않는 이름입니다. |
|

**Returns:**
int - 0부터 시작하는 인덱스입니다. 찾지 못하면 음수 값을 반환합니다.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


컬렉션에서 지정된 이름을 가진 Metadata 서명을 제거합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | Metadata Signature의 대소문자를 구분하지 않는 이름입니다. |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


지정된 인덱스에 있는 Metadata 서명을 제거합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 인덱스 | int | 0부터 시작하는 인덱스입니다. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Metadata 서명 객체를 컬렉션에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 컬렉션에 추가될 메타데이터 서명입니다. |

<br />

*** ** * ** ***

전체 기존 컬렉션에서 이름 값이 고유하지 않으면 예외를 발생시킵니다

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Metadata 서명 컬렉션을 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 추가할 서명들의 컬렉션입니다. |

<br />

*** ** * ** ***

전체 기존 컬렉션에서 이름 값이 고유하지 않으면 예외를 발생시킵니다

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Metadata Signature Items가 포함된 Clone Metadata Signature Collection 클래스를 복제합니다.


**Returns:**
java.lang.Object - 복제된 Signature Items를 포함한 복사된 인스턴스를 반환합니다

