---
title: "SignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "서명 옵션을 나타냅니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

서명 옵션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 서명을 위한 문서 페이지 번호를 가져오거나 설정합니다. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | 서명을 위한 문서 페이지 번호를 가져오거나 설정합니다. |
|
|  | [getAllPages()](#getAllPages--) | 모든 문서 페이지에 서명을 배치합니다. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | 모든 문서 페이지에 서명을 배치합니다. |
|
|  | [getAppearance()](#getAppearance--) | 추가 서명 외관. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | 추가 서명 외관. |
|
|  | [getExtensions()](#getExtensions--) | 서명 확장. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | 서명 확장. |
|
|  | [getPagesSetup()](#getPagesSetup--) | 서명할 페이지를 지정하는 옵션입니다. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 서명할 페이지를 지정하는 옵션입니다. |
|
|  | [getSignatureType()](#getSignatureType--) | 서명 유형을 가져옵니다 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | 서명 옵션의 문서 유형을 가져오거나 설정합니다 [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | 서명 옵션의 문서 유형을 가져오거나 설정합니다 [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | 텍스트 서명의 Z-순서 위치를 가져오거나 설정합니다. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | 텍스트 서명의 Z-순서 위치를 가져오거나 설정합니다. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | 암호화 작업에 사용할 해시 알고리즘을 가져오거나 설정합니다. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | 암호화 작업에 사용할 해시 알고리즘을 가져오거나 설정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


서명을 위한 문서 페이지 번호를 가져오거나 설정합니다.
최소값 및 기본값은 1입니다.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


서명을 위한 문서 페이지 번호를 가져오거나 설정합니다.
최소값 및 기본값은 1입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


모든 문서 페이지에 서명을 배치합니다.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


모든 문서 페이지에 서명을 배치합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


추가 서명 외관.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


추가 서명 외관.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


서명 확장.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


서명 확장.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


서명할 페이지를 지정하는 옵션입니다.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


서명할 페이지를 지정하는 옵션입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


서명 유형을 가져옵니다 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


서명 옵션의 문서 유형을 가져오거나 설정합니다 [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


서명 옵션의 문서 유형을 가져오거나 설정합니다 [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


텍스트 서명의 Z-순서 위치를 가져오거나 설정합니다.
겹치는 서명의 표시 순서를 결정합니다.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


텍스트 서명의 Z-순서 위치를 가져오거나 설정합니다.
겹치는 서명의 표시 순서를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


암호화 작업에 사용할 해시 알고리즘을 가져오거나 설정합니다.
PDF 파일의 디지털 서명에만 독점적으로 지원됩니다.
값은 [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm) 의 상수 중 하나입니다.


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


암호화 작업에 사용할 해시 알고리즘을 가져오거나 설정합니다.
PDF 파일의 디지털 서명에만 독점적으로 지원됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
