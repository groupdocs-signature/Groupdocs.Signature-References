---
title: "Signature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서 서명 프로세스를 제어하는 주요 클래스를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

문서 서명 프로세스를 제어하는 주요 클래스를 나타냅니다.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | 스트림으로 제공된 문서를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | 스트림으로 제공된 문서와 로드 옵션을 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스의 새 인스턴스를 초기화합니다 |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | 스트림으로 제공된 문서와 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | 스트림으로 제공된 문서와 로드 옵션을 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다. |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 및 설정 [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | 파일 경로로 제공된 문서를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다. |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | 파일 경로로 제공된 문서와 함께 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화하고 |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | 파일 경로로 제공된 문서와 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다. |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | 파일 경로로 제공된 문서를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다, |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 및 [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)를 사용하여 문서를 서명하고 결과를 스트림에 저장합니다. |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)를 사용하여 문서를 서명하고 미리 정의된 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)와 함께 결과를 스트림에 저장합니다. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 컬렉션을 사용하여 문서를 서명하고 결과를 스트림에 저장합니다. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 컬렉션을 사용하여 문서를 서명하고 미리 정의된 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)와 함께 결과를 스트림에 저장합니다. |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)를 사용하여 문서를 서명하고 지정된 파일 경로에 결과를 저장합니다. |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)를 사용하여 문서를 서명하고 미리 정의된 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)와 함께 지정된 파일 경로에 결과를 저장합니다. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 컬렉션을 사용하여 문서를 서명하고 지정된 파일 경로에 결과를 저장합니다. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 컬렉션을 사용하여 문서를 서명하고 미리 정의된 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)와 함께 지정된 파일 경로에 결과를 저장합니다. |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | 주어진 VerifyOptions 데이터로 문서 서명을 검증합니다. |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | VerifyOptions 데이터 목록으로 문서 서명을 검증합니다. |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 제공된 검증 옵션 및 필터를 사용하여 문서 서명을 검증합니다 |
지정된 술어에 따라 성공한 결과를 반환합니다.
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 검증 옵션 목록을 사용하여 문서 서명을 검증하고 필터링합니다 |
지정된 술어에 따라 성공한 결과를 반환합니다.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | 문서 페이지에 대한 정보를 가져옵니다: 페이지 크기, |
최대 페이지 높이와, 최대 높이를 가진 페이지의 너비.
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | 문서 페이지 미리보기를 생성합니다. |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | 문서에서 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 목록으로 서명을 검색합니다. |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 옵션 목록으로 서명을 검색하고 결과를 술어로 필터링합니다. |
|
|  | [search(Predicate<BaseSignature> predicate)](#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 문서에서 모든 유형(텍스트, 이미지, 디지털, 바코드, QR 코드 및 메타데이터)의 서명을 검색합니다 |
그리고 술어에 따라 필터링합니다.
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | 문서에서 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 옵션으로 서명을 검색합니다. |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | 문서에서 지정된 유형의 서명을 검색하고, 선택적으로 술어로 필터링합니다. |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 값을 사용하여 문서에서 정확한 유형의 서명을 검색합니다. |
|
|  | [search(int[] signatureTypes)](#search-int...-) | [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 값을 사용하여 문서에서 지정된 서명 유형을 검색합니다. |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | 문서에서 전달된 서명 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 업데이트합니다. |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 문서에서 전달된 서명들 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 업데이트합니다. |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 문서에서 전달된 서명들 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 업데이트합니다. |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | 문서에서 전달된 서명들 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 업데이트합니다. |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | 문서에서 전달된 서명 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다. |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 문서에서 전달된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다. |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | 문서에서 전달된 서명 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다. |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 문서에서 전달된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다. |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | 문서에서 특정 유형 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)의 서명을 삭제합니다. |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | 문서에서 특정 유형 목록 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)의 서명을 삭제합니다. |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | 문서에서 특정 유형 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)의 서명을 삭제합니다. |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | 문서에서 특정 유형 목록 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)의 서명을 삭제합니다. |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | 문서에서 특정 서명 ID로 서명을 삭제합니다. |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | 문서에서 전달된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다. |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | 주어진 SignOptions를 기반으로 서명 미리보기를 생성합니다. |
|
|  | [dispose()](#dispose--) | 내부 리소스를 정리하기 위해 IDisposable 인터페이스를 구현합니다 |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


스트림으로 제공된 문서를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서 콘텐츠 스트림. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


스트림으로 제공된 문서와 로드 옵션을 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스의 새 인스턴스를 초기화합니다
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서 콘텐츠 스트림. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 문서 로드 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


스트림으로 제공된 문서와 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서 콘텐츠 스트림. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 서명 설정. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


스트림으로 제공된 문서와 로드 옵션을 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다.
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 및 설정 [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서 콘텐츠 스트림. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 문서 로드 옵션. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 서명 설정. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


파일 경로로 제공된 문서를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 절대 경로나 상대 파일 경로. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


파일 경로로 제공된 문서와 함께 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화하고
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 절대 경로나 상대 파일 경로. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 문서 로드 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


파일 경로로 제공된 문서와 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 절대 경로나 상대 파일 경로. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 서명 설정. |

<br />

*** ** * ** ***

 **Learn more** 

* 
* 

<br />

|

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


파일 경로로 제공된 문서를 사용하여 [Signature](../../com.groupdocs.signature/signature) 클래스 인스턴스를 초기화합니다,
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 및 [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 절대 경로나 상대 파일 경로. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 문서 로드 옵션. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 서명 설정. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)를 사용하여 문서를 서명하고 결과를 스트림에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 서명 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)를 사용하여 문서를 서명하고 미리 정의된 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)와 함께 결과를 스트림에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 서명 옵션. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 저장 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 컬렉션을 사용하여 문서를 서명하고 결과를 스트림에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 서명 옵션 목록. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 컬렉션을 사용하여 문서를 서명하고 미리 정의된 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)와 함께 결과를 스트림에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 서명 옵션 목록. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 저장 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)를 사용하여 문서를 서명하고 지정된 파일 경로에 결과를 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 서명 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)를 사용하여 문서를 서명하고 미리 정의된 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)와 함께 지정된 파일 경로에 결과를 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 서명 옵션. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 저장 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 컬렉션을 사용하여 문서를 서명하고 지정된 파일 경로에 결과를 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 서명 옵션 목록. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 컬렉션을 사용하여 문서를 서명하고 미리 정의된 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)와 함께 지정된 파일 경로에 결과를 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 서명 옵션 목록. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 저장 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


주어진 VerifyOptions 데이터로 문서 서명을 검증합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | 서명 검증 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


VerifyOptions 데이터 목록으로 문서 서명을 검증합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | 서명 검증 옵션 컬렉션. [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection)의 인스턴스. |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)
```


제공된 검증 옵션 및 필터를 사용하여 문서 서명을 검증합니다
지정된 술어에 따라 성공한 결과를 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | 서명 검증 옵션. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 검증된 서명 목록에 적용되는 필터 프레디케이트. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - 검증에 성공하고 프레디케이트를 만족한 서명 목록.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


검증 옵션 목록을 사용하여 문서 서명을 검증하고 필터링합니다
지정된 술어에 따라 성공한 결과를 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | 서명 검증 옵션 목록. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 검증된 서명 목록에 적용되는 필터 프레디케이트. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - 검증에 성공하고 프레디케이트를 만족한 서명 목록.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


문서 페이지에 대한 정보를 가져옵니다: 페이지 크기,
최대 페이지 높이와, 최대 높이를 가진 페이지의 너비.


**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

<br />

*** ** * ** ***

**Learn more**

* Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java](../https://docs.groupdocs.com/signature/java/get-document-information/)

<br />


### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


문서 페이지 미리보기를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | 미리보기 옵션. |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/generate-document-pages-preview/)

<br />

|

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


문서에서 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 목록으로 서명을 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | 검색 옵션 컬렉션. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.

### search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)
```


옵션 목록으로 서명을 검색하고 결과를 술어로 필터링합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | 검색 옵션 목록. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 결과 서명을 필터링하는 데 사용되는 프레디케이트. |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### search(Predicate<BaseSignature> predicate) {#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> search(Predicate<BaseSignature> predicate)
```


문서에서 모든 유형(텍스트, 이미지, 디지털, 바코드, QR 코드 및 메타데이터)의 서명을 검색합니다
그리고 술어에 따라 필터링합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 찾은 서명 목록에 적용할 필터 프레디케이트. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - 제공된 프레디케이트를 만족하는 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) 인스턴스 목록을 반환합니다.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


문서에서 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 옵션으로 서명을 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | 검색 옵션. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - 찾은 서명 목록을 반환합니다.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


문서에서 지정된 유형의 서명을 검색하고, 선택적으로 술어로 필터링합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)의 제네릭 타입 매개변수. |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | 서명 검색 옵션. |
|
|  | predicate | java.util.function.Predicate<T> | 검색 후에 적용되는 선택적 프레디케이트 필터입니다. null일 수 있습니다. |
|

**Returns:**
java.util.List<T> - 프레디케이트에 의해 선택적으로 필터링된 찾은 서명 목록.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


[SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 값을 사용하여 문서에서 정확한 유형의 서명을 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | 검색할 서명의 유형. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - 정확한 유형의 찾은 서명 목록을 반환합니다.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


[SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 값을 사용하여 문서에서 지정된 서명 유형을 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatureTypes | int[] | 찾을 하나 이상의 서명 유형. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.

### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


문서에서 전달된 서명 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 업데이트합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 문서에서 업데이트될 서명 객체. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - 작업이 성공하면 true를 반환합니다.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


문서에서 전달된 서명들 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 업데이트합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 문서에서 업데이트할 서명 목록. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


문서에서 전달된 서명들 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 업데이트합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 문서에서 업데이트할 서명 목록. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


문서에서 전달된 서명들 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 업데이트합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 문서에서 업데이트될 서명 객체. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - 성공적으로 업데이트된 서명과 실패한 서명의 목록을 포함한 UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult)를 반환합니다.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


문서에서 전달된 서명 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 문서에서 제거될 서명 객체. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - 작업이 성공하면 true를 반환합니다.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


문서에서 전달된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 문서에서 제거할 서명 목록. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


문서에서 전달된 서명 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 문서에서 제거될 서명 객체. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - 작업이 성공하면 true를 반환합니다.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


문서에서 전달된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 문서에서 제거할 서명 목록. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


문서에서 특정 유형 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)의 서명을 삭제합니다.
Sign 메서드로 추가되고 서명으로 표시된 서명만
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) 은 제거됩니다.
다음 서명 유형이 지원됩니다: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signatureType | int | 문서에서 제거할 서명 유형. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


문서에서 특정 유형 목록 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)의 서명을 삭제합니다.
Sign 메서드로 추가되고 서명으로 표시된 서명만
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) 은 제거됩니다.
다음 서명 유형이 지원됩니다: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.OutputStream | 출력 문서 스트림. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | 문서에서 제거할 서명 유형 목록. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


문서에서 특정 유형 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)의 서명을 삭제합니다.
Sign 메서드로 추가되고 서명으로 표시된 서명만
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) 은 제거됩니다.
다음 서명 유형이 지원됩니다: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signatureType | int | 문서에서 제거할 서명 유형. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


문서에서 특정 유형 목록 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)의 서명을 삭제합니다.
Sign 메서드로 추가되고 서명으로 표시된 서명만
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) 은 제거됩니다.
다음 서명 유형이 지원됩니다: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 출력 파일 경로. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | 문서에서 제거할 서명 유형 목록. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


문서에서 특정 서명 ID로 서명을 삭제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatureId | java.lang.String | 문서에서 제거할 서명의 Id. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - 작업이 성공하면 true를 반환합니다.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


문서에서 전달된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)을 삭제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | 문서에서 제거할 서명의 식별자 목록. |

<br />

*** ** * ** ***

**Learn more** /// /// /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents) /// /// /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting) /// /// ///
|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


주어진 SignOptions를 기반으로 서명 미리보기를 생성합니다. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | 주어진 SignOptions를 사용한 미리보기 서명. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


내부 리소스를 정리하기 위해 IDisposable 인터페이스를 구현합니다


