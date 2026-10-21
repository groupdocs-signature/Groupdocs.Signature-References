---
title: "Signature"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "문서 서명 프로세스를 제어하는 주요 클래스를 나타냅니다."
type: docs
weight: 2170
url: /ko/net/groupdocs.signature/signature/
---
## Signature class

문서 서명 프로세스를 제어하는 주요 클래스를 나타냅니다.

```csharp
public class Signature : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Signature](signature#constructor)(Stream) | 스트림으로 제공된 문서를 사용하여 [`Signature`](../signature) 클래스의 새 인스턴스를 초기화합니다. |
| [Signature](signature#constructor_4)(string) | 파일 경로로 제공된 문서를 사용하여 [`Signature`](../signature) 클래스의 새 인스턴스를 초기화합니다. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | 스트림으로 제공된 문서와 로드 옵션 LoadOptions를 사용하여 [`Signature`](../signature) 클래스의 새 인스턴스를 초기화합니다. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | 스트림으로 제공된 문서와 [`SignatureSettings`](../signaturesettings)를 사용하여 [`Signature`](../signature) 클래스의 새 인스턴스를 초기화합니다. |
| [Signature](signature#constructor_5)(string, LoadOptions) | 파일 경로로 제공된 문서와 LoadOptions를 사용하여 [`Signature`](../signature) 클래스의 새 인스턴스를 초기화합니다. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | 파일 경로로 제공된 문서와 [`SignatureSettings`](../signaturesettings)를 사용하여 [`Signature`](../signature) 클래스의 새 인스턴스를 초기화합니다. |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | 스트림으로 제공된 문서, 로드 옵션 LoadOptions 및 설정 [`SignatureSettings`](../signaturesettings)를 사용하여 [`Signature`](../signature) 클래스의 새 인스턴스를 초기화합니다. |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | 파일 경로로 제공된 문서, LoadOptions 및 [`SignatureSettings`](../signaturesettings)를 사용하여 [`Signature`](../signature) 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | 전달된 서명 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)을 문서에서 삭제합니다. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | 전달된 서명 목록 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)을 문서에서 삭제합니다. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | 문서에서 특정 유형 목록 [`SignatureType`](../../groupdocs.signature.domain/signaturetype)의 서명을 삭제합니다. Sign 메서드로 추가되고 서명으로 표시된 [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) 서명만 삭제됩니다. 지원되는 서명 유형은 다음과 같습니다: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | 전달된 서명 목록 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)을 문서에서 삭제합니다. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | 문서에서 특정 유형 [`SignatureType`](../../groupdocs.signature.domain/signaturetype)의 서명을 삭제합니다. Sign 메서드로 추가되고 서명으로 표시된 [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) 서명만 삭제됩니다. 지원되는 서명 유형은 다음과 같습니다: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | 문서에서 특정 서명 Id에 해당하는 서명을 삭제합니다. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | 내부 리소스를 정리하기 위해 IDisposable 인터페이스를 구현합니다. |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | 문서 페이지 미리보기를 생성합니다. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | 문서 페이지에 대한 정보(크기, 최대 페이지 높이, 최대 높이를 가진 페이지의 너비)를 가져옵니다. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | 문서에서 모든 사용 가능한 검색 옵션을 사용하여 서명을 검색하고 지정된 프레디케이트에 따라 결과를 필터링합니다. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | 문서에서 서명을 [`SearchOptions`](../../groupdocs.signature.options/searchoptions) 목록으로 검색합니다. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | 문서에서 지정된 서명 유형을 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) 값으로 검색합니다. |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | 제공된 검색 옵션을 사용하여 문서에서 서명을 검색하고 지정된 predicate에 따라 결과를 필터링합니다. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | 문서에서 서명을 [`SearchOptions`](../../groupdocs.signature.options/searchoptions) 옵션으로 검색합니다. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | 문서에서 서명의 정확한 유형을 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) 값으로 검색합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | 컬렉션 [`SignOptions`](../../groupdocs.signature.options/signoptions)를 사용하여 문서에 서명하고 결과를 스트림에 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions)을(를) 사용하여 문서에 서명하고 결과를 스트림에 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | 컬렉션 [`SignOptions`](../../groupdocs.signature.options/signoptions)를 사용하여 문서에 서명하고 결과를 지정된 파일 경로에 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions)을(를) 사용하여 문서에 서명하고 결과를 지정된 파일 경로에 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | 컬렉션 [`SignOptions`](../../groupdocs.signature.options/signoptions)를 사용하여 문서에 서명하고 미리 정의된 [`SaveOptions`](../../groupdocs.signature.options/saveoptions)와 함께 스트림에 결과를 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions)을(를) 사용하여 문서에 서명하고 미리 정의된 [`SaveOptions`](../../groupdocs.signature.options/saveoptions)와 함께 스트림에 결과를 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | 컬렉션 [`SignOptions`](../../groupdocs.signature.options/signoptions)를 사용하여 문서에 서명하고 미리 정의된 [`SaveOptions`](../../groupdocs.signature.options/saveoptions)와 함께 지정된 파일 경로에 결과를 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions)을(를) 사용하여 문서에 서명하고 미리 정의된 [`SaveOptions`](../../groupdocs.signature.options/saveoptions)와 함께 지정된 파일 경로에 결과를 저장합니다. |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | 문서에서 전달된 서명 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)을 업데이트합니다. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | 문서에서 전달된 서명들 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)을 업데이트합니다. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | VerifyOptions 데이터 목록을 사용하여 문서 서명을 검증합니다. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | 주어진 VerifyOptions 데이터를 사용하여 문서 서명을 검증합니다. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | 사용 가능한 모든 검증 옵션을 사용하여 문서 서명을 검증하고 지정된 predicate에 따라 결과를 필터링합니다. 이 메서드는 먼저 검증 옵션과 일치하는 서명을 검색하고, predicate를 사용해 필터링한 다음, 필터링된 서명만 검증합니다. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | 제공된 검증 옵션을 사용하여 문서 서명을 검증하고 지정된 predicate에 따라 결과를 필터링합니다. 이 메서드는 먼저 검증 옵션과 일치하는 서명을 검색하고, predicate를 사용해 필터링한 다음, 필터링된 서명만 검증합니다. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | 주어진 SignOptions를 기반으로 서명 미리보기를 생성합니다. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | 서명 검색 프로세스가 완료될 때 발생합니다. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | 서명 검색 프로세스 진행 상황이 변경될 때 발생합니다. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | 서명 검색 프로세스가 시작될 때 발생합니다. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | 문서 서명 프로세스가 완료될 때 발생합니다. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | 문서 서명 프로세스 진행 상황이 변경될 때 발생합니다. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | 문서 서명 프로세스가 시작될 때 발생합니다. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | 서명 검증 프로세스가 완료될 때 발생합니다. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | 서명 검증 프로세스 진행 상황이 변경될 때 발생합니다. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | 서명 검증 프로세스가 시작될 때 발생합니다. |

### 비고

**Learn more**

GroupDocs.Signature 기능에 대해 자세히 알아보세요: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### 또 보기

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
