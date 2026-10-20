---
title: "MetadataSignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "메타데이터 서명 옵션을 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

메타데이터 서명 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | SignMetadataOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | SignMetadataOptions 클래스의 새 인스턴스를 메타데이터와 함께 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | 서명의 메타데이터를 가져오거나 설정합니다. |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | 서명의 메타데이터를 가져오거나 설정합니다. |
|
|  | [getDataEncryption()](#getDataEncryption--) | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | 전달된 인수를 사용하여 새로운 PdfMetadataSignature를 생성하고 컬렉션에 추가합니다. |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | 전달된 인수를 사용하여 새로운 ImageMetadataSignature를 생성하고 컬렉션에 추가합니다. |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | 기존 MetadataSignature 인스턴스를 컬렉션에 추가합니다. |
|
|  | [validate()](#validate--) | 옵션 매개변수를 검증하기 위한 내부 메서드입니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


SignMetadataOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


SignMetadataOptions 클래스의 새 인스턴스를 메타데이터와 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Metadata 서명 컬렉션 [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


서명의 메타데이터를 가져오거나 설정합니다.


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


서명의 메타데이터를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


전달된 인수를 사용하여 새로운 PdfMetadataSignature를 생성하고 컬렉션에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | Metadata 서명 객체의 이름 |
|
|  | 값 | java.lang.Object | Metadata 서명의 값 |
|
|  | 태그 | java.lang.String | Metadata 서명의 접두사 태그 |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


전달된 인수를 사용하여 새로운 ImageMetadataSignature를 생성하고 컬렉션에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | id | int | 이미지 메타데이터 서명 이름의 고유 식별자입니다. 가능한 id 값에 대한 Exif 태그 사양은 참고 문서를 확인하십시오. |
|
|  | 값 | java.lang.Object | 메타데이터 값 |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


기존 MetadataSignature 인스턴스를 컬렉션에 추가합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 추가될 기존 MetadataSignature 인스턴스 |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


옵션 매개변수를 검증하기 위한 내부 메서드입니다.


### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
